# Social Media Data Pipeline

This script provides an orchestrated pipeline to fetch data from multiple social media platforms, including Facebook, Instagram, and TikTok. It is intended to retrieve posts, comments, and other pertinent information for additional processing or analysis by leveraging platform-specific APIs.


Configuration
Before running the script, users must configure their API access details in the config.ini file. Here's a breakdown of what each section is for:

[Facebook]: Contains the access token and business ID required to fetch data from Facebook. Also specifies the API version and fields for the feed endpoint.

[Instagram]: Contains the access token and business ID required for Instagram. It also details the API version, fields for the tags endpoint, and fields for the media endpoint.

[TikTok]: Holds the access token, advertiser ID, and business ID for TikTok. It also specifies the API version and GraphQL dimensions.

[General]: Houses the headers access token, which is used in the headers of certain API requests across platforms.

Each section contains placeholders that should be replaced with actual values. 
