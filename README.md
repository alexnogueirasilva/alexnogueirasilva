```php
<?php

namespace AlexNogueira;

class About extends Me
{
    public function getCurrentWorkplace(): array
    {
        return [
            'workplace' => [
                'company' => 'Luizalabs',
                'position' => 'Software engineer'         
            ]
        ];
    }

    public function getDailyKnowledge(): array
    {
        return [
            Php::class,
            Laravel::class,
            Elixir::class,
            Phoenix::class
            Javascript::class,
            TypeScript,
            Vuejs::class,
            Golang::class,
            TailwindCss::class,
        ];
    }

    public function getFutureGoal(): string
    {
        return 'Become a full cycle software engineer.';
    }
}
```
