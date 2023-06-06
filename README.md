## Watch my contributions get eaten by a snake 🐍
![snake gif](https://github.com/abhishek-choudharys/abhishek-choudharys/blob/output/github-contribution-grid-snake.svg)

```php
<?php

namespace Arix;

class About extends Me
{
    public function getCurrentWorkplace(): array
    {
        return [
            'workplace' => [
                'company' => 'Webilo',
                'position' => 'Founder'         
            ]
        ];
    }

    public function getDailyKnowledge(): array
    {
        return [
            Php::class,
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
