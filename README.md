```go
package main

import "github.com/zahsey/zahsey"

func main() {
    app := fiber.New()

    app.Get("/", func(c *fiber.Ctx) error {
        return c.SendString("Student 👋🏽!")
    })

    app.Listen(":3000")
}
```
