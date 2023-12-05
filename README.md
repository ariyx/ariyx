```php
<?php

namespace Arix;

class About extends Me
{
    public function getCurrentWorkplace(): array
    {
        return [
            'workplace' => [
                'company' => 'Larano',
                'position' => 'Founder'         
            ]
        ];
    }

    public function getDailyKnowledge(): array
    {
        return [
            PHP::class,
            Laravel::class,
            Vuejs::class,
            Golang::class
        ];
    }

    public function getFutureGoal(): string
    {
        return 'To contribute to open source.';
    }

    public function whoIsArix(): string
    {
        return 'Upgraded version of armin.';
    }
}
```
