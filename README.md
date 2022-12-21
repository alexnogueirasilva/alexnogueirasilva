```php
<?php

namespace AlexNogueira;

class About extends Me
{
    public function getCurrentWorkplace(): array
    {
        return [
            'workplace' => [
                'company' => 'InsideCoffee',
                'position' => 'Founder'         
            ]
        ];
    }

    public function getDailyKnowledge(): array
    {
        return [
            Php::class,
            Laravel::class,
            Elixir::class,
            Javascript::class,
            TypeScript,
            Vuejs::class,
            TailwindCss::class,
        ];
    }

    public function getFutureGoal(): string
    {
        return 'Become a full cycle software engineer.';
    }
}
```
