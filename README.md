# buildpack-nmap
<a href="https://heroku.com/deploy?template=https://github.com/hahwul/buildpack-nmap">
  <img src="https://www.herokucdn.com/deploy/button.svg" alt="Deploy">
</a><br>
install nmap and set alias buildpack of heroku for me(add export ENV)

## Composed
```
$ heroku create --buildpack  https://github.com/hahwul/buildpack-nmap.git
$ git push heroku master
```
## setting config vars
`App => Settings => Config vars`
<img src="https://user-images.githubusercontent.com/13212227/65061836-b5910980-d9b5-11e9-94d4-4cb5b20929a7.png">

## References
https://github.com/socialpaymentsbv/heroku-buildpack-nmap
