# Beta merged to main, this is now redundant. Use [the original repository](https://github.com/IsThatTheRealNick/REPOConfig)! (it still works, but will recieve no more updates as of `2025-07-05`)
<br/>

# REPOConfig-overlap-patch
REPO beta build has settings and mod button overlap. The mod owner won't release for beta, so I fixed it. <br />
All credit goes to original creator [IsThatTheRealNick](https://github.com/IsThatTheRealNick/) and his [repository](https://github.com/IsThatTheRealNick/REPOConfig).<br />
<br /> The only change has been made to a single line (in ConfigMenu.cs):<br/>
`MenuAPI.AddElementToMainMenu(parent => MenuAPI.CreateREPOButton("Mods", CreateModMenu, parent, new Vector2(48.3f, 55.5f)));`<br />
to <br />
`MenuAPI.AddElementToMainMenu(parent => MenuAPI.CreateREPOButton("Mods", CreateModMenu, parent, new Vector2(120f, 54.1f)));`

## Installation
Just overwrite the file in `<your-mod-package-here>\BepInEx\plugins\nickklmao-REPOConfig`.<br />
You can navigate to the right folder by opening R2modman, selecting a profile, and going into settings. There will be an option to "Browse profile folder".

# Visual showcase
![What this patch does](https://github.com/MaybeHoot/REPOConfig-overlap-patch/blob/main/res/img.jpg?raw=true)
