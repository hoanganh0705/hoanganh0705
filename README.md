<img align="right" src="https://visitor-badge.laobi.icu/badge?page_id=hoanganh0705.hoanganh0705" />

<h1 align="center">
  Hello, World! I'm hoanganh0705
</h1>

<h3 align="center">
  A Full-Stack Developer passionate about seamless web solutions and DevOps practices
</h3>

<div align="center">

[![LinkedIn](https://img.shields.io/badge/nguyenanh-white?style=for-the-badge&logo=Linkedin&logoColor=0A66C2)](https://www.linkedin.com/in/nguyen-anh-3974a4305/)
[![Facebook](https://img.shields.io/badge/nguyenanh-white?style=for-the-badge&logo=facebook&logoColor=0866FF)](https://www.facebook.com/profile.php?id=100081242662585)
[![Email](https://img.shields.io/badge/anh487303@gmail.com-white?style=for-the-badge&logo=gmail&logoColor=EA4335)](mailto:anh487303@gmail.com)

<img width="300px" src="./img/image.gif" alt="Workspace">
</div>

---

### ✨ About Me

```go
package main

import (
	"fmt"
)

type Hoanganh0705 struct {
	Username     string
	Name         string
	Position     string
	Web          string
	Links        string
	Blog         string
	CV           string
	Twitter      string
	About        map[string]string
	Code         map[string][]string
	Architecture []string
}

func NewHoanganh0705() *Hoanganh0705 {
	return &Hoanganh0705{
		Username: "hoanganh0705",
		Name:     "Nguyễn Hoàng Anh",
		Position: "Golang Software Developer",
		Web:      "https://anhnguyendev.me",
		Links:    "https://links.anhnguyendev.me",
		Blog:     "https://blog.anhnguyendev.me",
		CV:       "https://resume.anhnguyendev.me",

		About: map[string]string{
			"Location":       "Ho Chi Minh City, the most vibrant and charming city in Vietnam.",
			"FavouriteFood":  "Banhmi with extra JavaScript toppings",
			"SpecialisingIn": "Backend development using Node.js and Frontend development with Next.js and TypeScript.",
		},

		Code: map[string][]string{
			"backend":  {"Go", "Node.js", "Gin", "Fiber", "Express", "RESTful API", "Microservices"},
			"database": {"PostgreSQL", "MySQL", "MongoDB", "Redis"},
			"devops":   {"Docker", "Linux", "CI/CD", "GitHub Actions", "Nginx"},
			"frontend": {"TypeScript", "Next.js", "React", "TailwindCSS"},
			"tools":    {"Git", "GitHub", "Postman", "Golangci-lint", "Swagger", "Makefile"},
			"misc":     {"JWT", "OAuth2", "gRPC", "WebSockets", "Clean Architecture"},
		},

		Architecture: []string{"Microservices", "Clean Architecture", "Hexagonal", "Serverless", "Event-driven"},
	}
}

func (h *Hoanganh0705) String() string {
	return fmt.Sprintf("%s | %s", h.Name, h.Position)
}

func main() {
	me := NewHoanganh0705()

	fmt.Println(me)
	fmt.Println("About Me:")
	for k, v := range me.About {
		fmt.Printf("- %s: %s\n", k, v)
	}

	fmt.Println("\nTech Stack:")
	for category, items := range me.Code {
		fmt.Printf("%s: %v\n", category, items)
	}

	fmt.Println("\nArchitectures:", me.Architecture)
}

```

### <img width="18px" src="./img/technologies.gif"> Technologies

![Go](https://img.shields.io/badge/Go-black?style=flat&logo=go&logoColor=00ADD8)
![Javascript](https://img.shields.io/badge/Javascript-black?style=flat&logo=Javascript&logoColor=F7DF1E)
![TypeScript](https://img.shields.io/badge/Typescript-black?style=flat&logo=Typescript&logoColor=007ACC)
![React](https://img.shields.io/badge/React-black?style=flat&logo=react&logoColor=61DAFB)
![Tailwind CSS](https://img.shields.io/badge/Tailwind_CSS-black?style=flat&logo=tailwindcss&logoColor=06B6D4)
![Node.js](https://img.shields.io/badge/Node.js-black?style=flat&logo=node.js&logoColor=339933)
![Express](https://img.shields.io/badge/Express-black?style=flat&logo=express&logoColor=white)
![Git](https://img.shields.io/badge/Git-black?style=flat&logo=git&logoColor=F05032)
![JWT](https://img.shields.io/badge/JWT-black?style=flat&logo=jsonwebtokens&logoColor=white)
![PostgreSql](https://img.shields.io/badge/PostgreSQL-black?style=flat&logo=PostgreSQL&logoColor=white&labelColor=336791)
![MongoDB](https://img.shields.io/badge/MongoDB-black?style=flat&logo=mongodb&logoColor=47A248)
![Docker](https://img.shields.io/badge/Docker-black?style=flat&logo=docker&logoColor=2496ED)
![Github](https://img.shields.io/badge/Github-black?style=flat&logo=github&logoColor=00000)
![Eslint](https://img.shields.io/badge/Eslint-black?style=flat&logo=Eslint&logoColor=4B32C3)
![Prettier](https://img.shields.io/badge/Prettier-black?style=flat&logo=prettier&logoColor=F7B731)
![Webpack](https://img.shields.io/badge/Webpack-black?style=flat&logo=webpack&logoColor=8DD6F9)
![Babel](https://img.shields.io/badge/Babel-black?style=flat&logo=babel&logoColor=F9DC3E)
![npm](https://img.shields.io/badge/npm-black?style=flat&logo=npm&logoColor=CB3837)
![Yarn](https://img.shields.io/badge/Yarn-black?style=flat&logo=yarn&logoColor=2C8EBB)
![pnpm](https://img.shields.io/badge/pnpm-black?style=flat&logo=pnpm&logoColor=F69220)
![Linux](https://img.shields.io/badge/Linux-black?style=flat&logo=linux&logoColor=cccccc)
![Fedora](https://img.shields.io/badge/Fedora-black?style=flat&logo=fedora&logoColor=1868C3)
![Ubuntu](https://img.shields.io/badge/Ubuntu-black?style=flat&logo=ubuntu&logoColor=E95420)
![Postman](https://img.shields.io/badge/Postman-black?style=flat&logo=postman&logoColor=FF6C37)

## 💬 My Favorite Quote

<div align="center" style="padding: 10px; border-radius: 5px; background-color: rgb(28, 26, 26); color: white;">
  <span style="font-size: 15px;">"Doubt kills more dreams than failure ever will."</span>
</div>

---

<div align="center">
  <img src="./svg/thanks.svg" alt="Thank you" />
</div>
