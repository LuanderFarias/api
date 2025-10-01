~ niko-api [not working yet]

directly exposes some information and stuff about me to a API and WebSocket.
```http
  GET https://api.example.com/{package}/{parameter}
```
not providing an parameter will return all parameters of the package, not providing a package will return everything from the api

packages:

person
| parameter | description                |
| :-------- | :------------------------- |
| age | returns my age including seconds |
| weather | shows my local weather |

GPS
| parameter | description                |
| :-------- | :------------------------- |
| city | returns my current city |
| weather | returns my local weather |
| location | shows location based on known places (home, wife's house, market, etc) |

github
| parameter | description                |
| :-------- | :------------------------- |
| none | for now use github api for it... |

spotify
| parameter | description                |
| :-------- | :------------------------- |
| last_songs | returns a list of my last 10 songs |
</details>
