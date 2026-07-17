~ stalker [under development]

an api that directly exposes information and tracks data about me.
```
GET https://api.example.com/{package}/{parameter}
```
> not providing an parameter will return all parameters of the package and not providing a package will return all packages with all parameters

| package | parameters | description                |
| :------ | :-------- | :------------------------- |
| personal | age, a | returns my age |
| personal | exact_age, e_age, ea | returns my exact age including seconds |
| location | city, c | returns my current city |
| location | time, t | returns my current local time |
| location | weather, w | returns my current local weather |
| location | location, l | shows location based on known places (home, wife's house, market, etc) |
| social | tiktok, ttk, t | returns my tiktok profile link |
| social | instagram, ig, i | returns my instagra, profile link |
| social | youtube, yt, ytb, y | returns my youtube channel link |
| social | twitter, tw, t, x | returns my x/twitter profile link |
| social | bluesky, bsky, b | returns my bluesky profile link |

> github, spotify, youtube and/or more coming soon, you can create your own stalker following [this]()

create stuff.
