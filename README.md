```php
<?php

namespace Arix;

class About extends Me
{
    public function getProfile(): array
    {
        return [
            'role' => 'Software Developer',
            'education' => 'Computer Engineering Student',
        ];
    }

    public function getStack(): array
    {
        return [
            PHP::class,
            Laravel::class,
            Vuejs::class,
            TypeScript::class,
            Golang::class,
            PostgreSQL::class,
            Redis::class,
        ];
    }

    public function whoIsArix(): string
    {
        return 'Upgraded version of Armin.';
    }
}
```
