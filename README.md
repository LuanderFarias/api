~ niko-api [not working yet]

directly exposes some information and stuff about me to a API and WebSocket.
```
  GET https://api.example.com/{package}/{parameter}
```
> not providing an parameter will return all parameters of the package and not providing a package will return everything from the api

| package | parameter | description                |
| :------ | :-------- | :------------------------- |
| personal | age | returns my age |
| personal | exact_age | returns my exact age including seconds |
| location | city | returns my current city |
| location | time | returns my current local time |
| location | weather | returns my current local weather |
| location | location | shows location based on known places (home, wife's house, market, etc) |

github, spotify, youtube and/or more coming soon, you can create your own stalker following [this]()

create stuff.
