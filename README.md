package main

import "fmt"

type haq struct {
	Name, Role, Portfolio string
	LanguageSpoken        []string
}

func main() {
	me := folka{
		Name: "folka",
		Role: "developer, SOC analyst",
		LanguageSpoken: []string{"en_US"},
		Portfolio: "[https://1hehaq.vercel.app](https://folka-portfolio.vercel.app/)",
	}

	fmt.Println("Thanks for stopping by!")
	fmt.Println("Check out my portfolio at:", me.Portfolio)
}
