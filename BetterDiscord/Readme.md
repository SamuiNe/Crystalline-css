
# Crystalline-css Better Discord
This is a stub file meant to allow the Crystalline css theme file to work with Better Discord.  For convenience it imports the css file from GitHub via GitCDN.xyz so it is almost always kept up to date.  A couple of typical configuration options are given to allow changing the background as well as it's size. ~[shinji257](https://github.com/shinji257)<br>

## Requirements
To apply this CSS to Discord, you should have [BetterDiscord](https://betterdiscord.net/home/) installed!<br>
This discord theme only works on dark theme. Light theme is not supported! (for now)

*Note: As this file uses @import css I can't promise that the file will work in BeautifulDiscord although there is nothing that prevents it from doing so.*<br>


## Configuration
The below css excerpt is included in the file.  By default they are commented out.  You can uncomment the settings below and change them to something that you may prefer otherwise the default in the original css will be used instead.

    body{
        /* Override background image in original css
        The picture source is from 书童hiroco at the link (thanks shinji257!):
        https://www.pixiv.net/member_illust.php?mode=medium&illust_id=61734227 */
        //background: #fff url(https://wawawa.s-ul.eu/hWCZReAV.png);

        /* It is recommended to set the background-size width to match your monitor's or discord window's width.
           If the background picture is blurry, please use a bigger sized background picture. */
        //background-size: 1920px auto;
    }


