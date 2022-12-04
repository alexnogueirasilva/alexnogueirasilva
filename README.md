```php
<?php

namespace AlexNogueira;

class About extends Me
{
    public function getCurrentWorkplace(): array
    {
        return [
            'workplace' => [
                'company' => 'MoneyCoffee',
                'position' => 'Founder'         
            ]
        ];
    }

    public function getDailyKnowledge(): array
    {
        return [
            Php::class,
            Javascript::class,
            Laravel::class,
            Vuejs::class,
            Elixir::class,
            TailwindCss::class,
        ];
    }

    public function getFutureGoal(): string
    {
        return 'Become a full cycle software engineer.';
    }
}
```
