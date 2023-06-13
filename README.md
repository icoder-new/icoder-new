### <img src="https://media3.giphy.com/media/cdZAGXI45pQ6Q/200w.webp?cid=ecf05e47bl9p22lqiw84me0ugiodtaksl8csls7m2f8toawc&rid=200w.webp&ct=s" width="50">  Hi I'm Gadoev Ehson
```go
package icoder-new

import "fmt"

type Programmer interface {
	Eat()
	Code()
	Sleep()
}

type Gopher struct {
	name string
}

func NewGopher(name string) *Gopher {
	return &Gopher{name: name}
}

func (g *Gopher) Eat() {
	fmt.Printf("%s is eating...\n", g.name)
}

func (g *Gopher) Code() {
	fmt.Printf("%s is coding...\n", g.name)
}

func (g *Gopher) Sleep() {
	fmt.Printf("%s is sleeping...\n", g.name)
}

func Run() {
	gopher := NewGopher("Ehson")
	var programmer Programmer = gopher
	programmer.Eat()
	programmer.Code()
	programmer.Sleep()
}
```
### <img src="https://media1.giphy.com/media/aoydQ5HRJUAbm/200w.webp?cid=ecf05e47o0tp0ekam8nvvne2ishova5durnotvi6fz1vacq5&rid=200w.webp&ct=s" width="100"> Languages & Tools

![Postgres](https://img.shields.io/badge/postgres-%23316192.svg?style=for-the-badge&logo=postgresql&logoColor=white)  ![SQLite](https://img.shields.io/badge/sqlite-%2307405e.svg?style=for-the-badge&logo=sqlite&logoColor=white)
![Heroku](https://img.shields.io/badge/heroku-%23430098.svg?style=for-the-badge&logo=heroku&logoColor=white) ![Firebase](https://img.shields.io/badge/firebase-%23039BE5.svg?style=for-the-badge&logo=firebase) ![Cloudflare](https://img.shields.io/badge/Cloudflare-F38020?style=for-the-badge&logo=Cloudflare&logoColor=white) ![GitHub](https://img.shields.io/badge/github-%23121011.svg?style=for-the-badge&logo=github&logoColor=white) 
![Goland](https://img.shields.io/badge/Goland-143?style=for-the-badge&logo=goland&logoColor=black&color=black&labelColor=darkorchid) ![Visual Studio Code](https://img.shields.io/badge/Visual%20Studio%20Code-0078d7.svg?style=for-the-badge&logo=visual-studio-code&logoColor=white) 
![HTML5](https://img.shields.io/badge/html5-%23E34F26.svg?style=for-the-badge&logo=html5&logoColor=white) ![Python](https://img.shields.io/badge/python-3670A0?style=for-the-badge&logo=python&logoColor=ffdd54) ![JavaScript](https://img.shields.io/badge/javascript-%23323330.svg?style=for-the-badge&logo=javascript&logoColor=%23F7DF1E) ![Shell Script](https://img.shields.io/badge/shell_script-%23121011.svg?style=for-the-badge&logo=gnu-bash&logoColor=white)

BTW, I use ![windows](https://img.shields.io/badge/Windows-1793D1?logo=windows&logoColor=fff&style=for-the-badge)




![Top Languages](https://github-readme-stats.vercel.app/api/top-langs?username=icoder-new&hide=html&show_icons=true&locale=en&theme=tokyonight) 
