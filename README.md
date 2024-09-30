# Happy Birthday Website

To wish somebody happy birthday with a website. For fun only.

## Getting Started

### TODO
* Replace avatar.png and happy_birthday.mp3 

### Demo
![Demo](assets/demo.gif)

### Build and publish

```bash
docker build -t happy-birthday .
docker run -p 80:80 happy-birthday

# to export
docker save -o ./build/happy_birthday.tar
```

<!-- ## Citation

* UI modified from [startbootstrap-freelancer](https://github.com/StartBootstrap/startbootstrap-freelancer.git)
* Sample avatar generate from [getavataars](https://getavataaars.com/?avatarStyle=Transparent)
* Music from [Happy Birthday India Version](https://www.youtube.com/watch?v=USpw3I41pnc) -->