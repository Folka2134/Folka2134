<!-- Typing SVG -->
<p align="center">
  <a href="https://github.com/folka2134"><img src="https://readme-typing-svg.herokuapp.com?font=Fira+Code&size=22&pause=1000&color=330099&center=true&vCenter=true&width=435&lines=Developer;SOC+Analyst" alt="Typing SVG" align="center"/></a>
</p>

```go
package main

import "fmt"

type folka struct {
	Name, Role, Portfolio string
	LanguageSpoken        []string
}

func main() {
	me := folka{
		Name: "folka",
		Role: "developer, SOC analyst",
		LanguageSpoken: []string{"en_US", "ja-JP"},
		Portfolio: "https://folka-portfolio.vercel.app/",
	}

	fmt.Println("Thanks for stopping by!")
	fmt.Println("Check out my portfolio at:", me.Portfolio)
}
```
