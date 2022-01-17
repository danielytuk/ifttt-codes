# IFTTT Simple Guide
This repository lists various code snippets for applets, you can create on [IFTTT](https://ifttt.com). 

If you find this helpful, please consider donating.
There's [multiple methods available](https://dytuk.media/support) or [go to the buttons](#support) below.

 # Jump to Section
 - [Instagram Images](#instagram-images)
 - [Instagram Videos](#instagram-videos)
 - [Twitter](#twitter)
 - [YouTube](#youtube)
 - [Support Me](#support) 💖

## This page is still being written.
I will be rewriting this but I can only do that when I have the time. Also, if you couldn't tell, this is rushed (sorry).

# Instagram *images*
You can alternatively [use this applet](https://ifttt.com/applets/DKiUTcs8-share-photos-to-discord) instead of pasting all the code below.
```json
{
	"embeds": [{
		"description": "[<<<{{Caption}}>>>](<<<{{Url}}>>>)",
		"color": 9845184,
		"footer": { "text": "Uploaded <<<{{CreatedAt}}>>>", "icon_url": "https://1p.tf/imgs/insta_64.webp" },
		"image": { "url": "<<<{{SourceUrl}}>>>" }
	}],
	"username": "Instagram",
	"avatar_url": "https://1p.tf/imgs/insta_128.webp"
}
```
# Instagram *videos*
No alternative applet available.
```json
{
	"content": "<<<{{Caption}}>>>\n<<<{{URL}}>>>"
}
```
# Twitter
You can alternatively [use this applet](https://ifttt.com/applets/rC6SFXRM-post-your-twitter-tweets-to-discord) instead of pasting all the code below.
```json
{
	"embeds": [{
		"description": "[<<<{{UserName}}>>> posted a new tweet.](<<<{{LinkToTweet}}>>>)\n<<<{{Text}}>>>",
		"color": 1941745,
		"footer": { "text": "Uploaded <<<{{CreatedAt}}>>>", "icon_url": "https://1p.tf/imgs/twit_64.webp" }
	}],
	"username": "Twitter",
	"avatar_url": "https://1p.tf/imgs/twit_128.webp"
}
```
# YouTube
You can alternatively [use this applet](https://ifttt.com/applets/C5bKiEfC-message-to-discord-when-you-share-a-new-video-on-youtube) instead of pasting all the code below.
```json
{
	"content": "<<<{{Title}}>>> | <<<{{Url}}>>>",
	"username": "YouTube",
	"avatar_url": "https://1p.tf/imgs/yt_128.webp"
}
```
# Support
<p><a href="https://www.buymeacoffee.com/danielytuk"> <img align="left" src="https://cdn.buymeacoffee.com/buttons/v2/default-yellow.png" height="50" width="210" alt="buy-me-a-coffee" /></a><a href="https://www.paypal.me/dytukmedia"> <img align="left" src="https://i.ibb.co/fdpj8p8/paypal-donate-button.png" height="50" width="210" alt="paypal" /></a><a href="https://www.patreon.com/danielytuk"> <img align="left" src="https://i.ibb.co/hZVcbq9/patreon-button.png" height="50" width="210" alt="patreon" /></a></p>
