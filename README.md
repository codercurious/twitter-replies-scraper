# Twitter comments scraper
Interested in using this scraper? Get it here: [Twitter comments scraper](https://apify.com/curious_coder/twitter-replies-scraper)
## How it works

You need to pass twitter cookies to this actor to use the existing session to  perform scraping.

You can customise and randomise the delay between scraping pages.

## Getting Started

Install [EditThisCookie](https://chrome.google.com/webstore/detail/editthiscookie/fngmhnnpilhplaeedifhccceomclgfbg) chrome extension 

Login to your twitter account

Click on the extension and export the twitter cookies

Paste the cookies into this actor's `cookie` input field

Here is the sample output of this actor:

```json
{
	"bookmark_count": 0,
	"bookmarked": false,
	"created_at": "Fri Jul 14 12:15:36 +0000 2023",
	"conversation_id_str": "1679808034837774336",
	"display_text_range": [
		0,
		105
	],
	"entities": {
		"user_mentions": [],
		"urls": [
			{
				"display_url": "the-viral-supplement.ck.page/signup",
				"expanded_url": "https://the-viral-supplement.ck.page/signup",
				"url": "https://t.co/EHVtpm5BS3",
				"indices": [
					82,
					105
				]
			}
		],
		"hashtags": [],
		"symbols": []
	},
	"favorite_count": 2,
	"favorited": false,
	"full_text": "Did someone say free viral Tweet breakdowns in your inbox every week?\n\nJoin here👇\nhttps://t.co/EHVtpm5BS3",
	"in_reply_to_screen_name": "_danreynolds_",
	"in_reply_to_status_id_str": "1679808034837774336",
	"in_reply_to_user_id_str": "1158101960",
	"is_quote_status": false,
	"lang": "en",
	"possibly_sensitive": false,
	"possibly_sensitive_editable": true,
	"quote_count": 0,
	"reply_count": 2,
	"retweet_count": 0,
	"retweeted": false,
	"user_id_str": "1158101960",
	"id_str": "1679826980378738688",
	"source_name": "Hypefury",
	"source_url": "https://hypefury.com",
	"views": "220",
	"user": {
		"__typename": "User",
		"id": "VXNlcjoxMTU4MTAxOTYw",
		"rest_id": "1158101960",
		"affiliates_highlighted_label": {},
		"has_graduated_access": true,
		"is_blue_verified": true,
		"profile_image_shape": "Circle",
		"legacy": {
			"can_dm": true,
			"can_media_tag": true,
			"created_at": "Thu Feb 07 19:45:54 +0000 2013",
			"default_profile": true,
			"default_profile_image": false,
			"description": "Quit my city job to write online // helping you find freedom in writing and business // Ghostwriting personal brands at SocialScaler",
			"entities": {
				"description": {
					"urls": []
				},
				"url": {
					"urls": [
						{
							"display_url": "the-viral-supplement.ck.page/signup",
							"expanded_url": "https://the-viral-supplement.ck.page/signup",
							"url": "https://t.co/xCct97IXNY",
							"indices": [
								0,
								23
							]
						}
					]
				}
			},
			"fast_followers_count": 0,
			"favourites_count": 24432,
			"followers_count": 2601,
			"friends_count": 399,
			"has_custom_timelines": true,
			"is_translator": false,
			"listed_count": 41,
			"location": "FREE viral tweet breakdowns ↓",
			"media_count": 420,
			"name": "— Daniel",
			"normal_followers_count": 2601,
			"pinned_tweet_ids_str": [
				"1570381397130637312"
			],
			"possibly_sensitive": false,
			"profile_banner_url": "https://pbs.twimg.com/profile_banners/1158101960/1684436057",
			"profile_image_url_https": "https://pbs.twimg.com/profile_images/1629598305838678016/2qaaBYMb_normal.jpg",
			"profile_interstitial_type": "",
			"screen_name": "_danreynolds_",
			"statuses_count": 10072,
			"translator_type": "none",
			"url": "https://t.co/xCct97IXNY",
			"verified": false,
			"want_retweets": false,
			"withheld_in_countries": []
		},
		"verified_phone_status": false
	}
}
```
