#### Jatinegara Barat Student 🕊️
```diff
-package- main

import "github.com/zahsey"

func main() {
    app := fiber.New()

    app.Get("/", func(c *fiber.Ctx) error {
        return c.SendString("Hello, World 👋!")
    })

    app.Listen(":3000")
}
```
