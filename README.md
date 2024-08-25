# HoYoLab-box

<div align = center>
  <img src = 'https://github.com/yangchang-n/HoYoLab-box/assets/104478650/7610fb51-fa68-4822-8bb0-d8dee0845f4f' width = '400'>
  <h3 align = 'center'>HoYoLab-box</h3>
  <p align = 'center'>🎮 Update your pinned gist to show your Genshin Impact / Honkai: Star Rail gameplay stats</p>
</div>


## Setup

### Prep Work
1. Create a new public GitHub Gist (https://gist.github.com/)
2. Create a token with the `gist` scope and copy it (https://github.com/settings/tokens/new)
3. Go to HoYoLab and login to your account
4. Press **F12** to open developer tools
5. Find and copy `ltoken_v2` and `ltmid_v2` in Cookies

### Project Setup
1. Fork this repo
2. Go to the repo **Settings > Secrets**
3. Add the following environment variables
- **GH_TOKEN** : The GitHub token generated above
- - **GIST_ID** : The ID portion from your gist url
- **HOYO_UID** : Your HoYoverse/HoYoLab UID
- **HOYO_TOKEN** : Your personal HoYoLab API access token (copied `ltoken_v2`)
- **HOYO_TMID** : Another key value to access API (copied `ltmid_v2`)


## References
- [steam-box](https://github.com/YouEclipse/steam-box)
- [youtube-box](https://github.com/SinaKhalili/youtube-box)
- [neko-box](https://github.com/RangerDigital/neko-box)
> For more pinned-gist projects like this one, check out : https://github.com/matchai/awesome-pinned-gists


## Feedback and Contributions
- Always welcome in any way


## License
- MIT License
