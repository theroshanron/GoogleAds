## DV360 - Types of YouTube Ads
- Format of YouTube Ads:
  - Skippable in-Stream:
    - Video ads plays before the actual video or in mid, post position and can be skipped 
    - Runs on YouTube watch page and Google Display Network
    - Allows to add CTA
    - Pay in CPM or CPV
  - Non-Skippable in-Stream:
    - Can't skip and good for awareness
    - 15 seconds is limited 
    - Pay only in CPM
    - Video ads plays before the actual video or in mid, post position and can be skipped 
  - Discovery Ads
    - Only plays when user clicks on it and appears in the result of search page, watch page or homepage
    - Pay as CPV
  - Bumper Ads
    - Non skippable ads but limited to 6 seconds
    - Pay with CPM
  - Outstream Ads
    - Only supports Mobile with sound off and appears only on GDN
    - Pay with vCPM (Only after Ads are viewed for 2 seconds)
  - Masthead
    - Appears on homepage of YouTube at the top
    - Needs reservation by reaching out to Google team
    - CPD(Cost per day) for a geography or in some cases CPM basis
- Bidding strategy is different for all formats of YouTube Ads
- YouTUbe campaign can be run only using Google Ads or DV360

## Create TrueView Line items
- Select the insertion order for YouTube
- Select the YouTube and partners 
- Name the Line Item and select the media type as Video
- Select the type like brand awareness, shopping, website conversions or Reach
- Select the Ad format for YouTube ads
- Select In-stream
  - Select the inventory sources like YouTube search, videos and include video partners(Outstream Ads)
  - Add flight dates 
  - Add the budget flight / daily
  - Bid Adjustment based on platform targeting
  - Add frequency cap
  - Add conversions tracking using Floodlight tags
    - Count all conversions and floodlight attribution model or primary model 
  - We have Ad groups as well in YouTube Line items
    - Ad groups are actual entity where we upload the video for Ads 
    - Select Ad formats for YouTube Ads 
    - Select Targeting to reach to the right audience(Third party audience is not available for YouTube line items)
    - Select In-Market audience from Google Audience
    - Add Bid strategy as per the media plan and regional cost as well in the factors 
    - Add the video link in Ad and Add ad name 
      - Enter the Display URL of the video
      - Landing Page URL
      - Click tracker URL
      - Option to add Companion banner (Display URL, logo and auto generated image from the video or upload the banner)
      - Option to add Call to action button
    - Follow the same steps as above for the different types of audience in Line items 

- Line item for discovery Ad format: 
  - Select the insertion order YouTube 
  - Name and Media type 
  - Select the campaign type as brand awareness
  - Select the video type as discovery ad
  - Go to the Ad groups and add ad name as Discovery ads
  - Select Ad format as discovery ad
  - Discovery ad only plays when user click on the thumbnail
  - Target the audience with custom audience and placement based audience 
    - Add the right keywords for custom audience to reach the relevant users
    - Add the contextual placement and search for the keywords to find a channel with more views and subscribers
      - Select the placement targeting and Ad the video link of the channel to target
        - We can target multiple channels videos
  - Add Bid strategy 
  - Add the video link in Ads and add name 
  - Select the thumbnails for the video ad
  - Add Headline and Description for the Ad

## Deals in DV360 
- An advertising inventory agreement between a buyer (advertiser) and a seller (publisher)
  - Deals based on CPM rates, centralized reporting, no-discrepancy
  - Allows to publish ads with certain publishers globally with the help of DV360

### Types of deals
- Open Auctions or RTB
- Guaranteed:
  - Contracted Quantity
  - Targeting can't be changed once the deal is setup 
  - Higher CPM rates = Highest priority
- Programmatic Guaranteed: 
  - Direct sell and contracted impression
  - Fixed CPM
  - 1-1 Deal

- Non-Guaranteed:
  - Non-Guaranteed Fixed inventory
    - No contracted impressions
    - 1-1 Deal with Agreed upon price 
    - Used to be known as Preferred deal
  - Non-Guaranteed auction
    - 1-Few with floor price limited
      - Used to be known as Private Marketplace

- Preferences:
  - Programmatic > Non-Guaranteed Fixed Inventory > Non-Guaranteed Auction > Open Auction
  
## Overview of the DV360 Marketplace
- Go to the inventory section 
  - My inventory section is already selected deals
  - Negotiations section is to give feedback or change some parameters while dealing
  - Click on the marketplace to see the featured and other publishers
  - We can apply filters to find the relevant publishers for us
    - Major publishers can be found based on demographics, gender, platform, type of ads option, video options
  - Click on any publisher to see more details like how many impressions, cookies they serve and exchange they are using.
    - You can also check their profile and products they are serving 
    - You can request for the proposal from products section 
  - It also shows the contact of the person you can connect to discuss more about the deals

## How to setup and configure Deals
- Request for the proposal from publishers
- Negotiate / Suggest changes or approve
- Configure the campaign 
- Under the proposal:
  - Add RFP Name
  - Email address for CC
  - We can add multiple sellers in one proposal
  - Add budget of the campaigns
  - Add campaign start and end dates
  - Add CPM and impressions Required
  - Select the inventory type for the deal
  - Select the Ad format you want to serve with the campaign
  - Select the device you want to serve
  - Select the country in which you want ads to be displayed
  - Select the creative size, you'd like to use
  - Select the audience list if the publisher is using Ad managers
  - Add Advertisers 
  - Add RFP details and any particular message you'd like
- If you are sending the proposal via email, do send the above details and your partner 
- For negotiations, select the proposal and see the offerings list
  - Accept, reply or cancel the deal based on offers
  - Deal ID gets created when the proposal is accepted
  - We can renegotiate as well after the proposal is accepted
  - For the non-guaranteed deals, we will see the floor price and other details 
    - We get option to Accept and agree or archive the deal 
- To configure the programmatic deal:
  - Go to my inventory and click o actions to configure the deal
  - Select the advertiser 
  - Search for the campaign and select it
    - Campaign must be created before the deal is to be configured
  - Click on next and assign creatives based on the dimensions
  - For Non-guaranteed deals, select the deal and configure inventory packages and select deal  in line Item

## How to upload 3rd party tags as creatives 
- An overview:
  - Use is on ABC.com and ABC.com requests for an ad from the Ad exchange
    - Ad exchange requests the creative from the DV360
      - DV360 sends the creative to Ad exchanges which is further sends to ABC.com as viewed by users
        - It's counted as 1 impression
  - User clicks on the Ad link and requests for the landing page from DV360 
    - DV360 sends the landing page to ABC.com and counts it as one click
  - In case of where creatives are stored at third party ad server like CM360, DV360 requests for the tag from CM360
    - DV360 then sends the tag to Ad exchange which sends it to ABC.com 
      - ABC.com renders the creative where tag requests for the creative from CM360
    - If the user clicks on the ad, it requests the landing url from CM360 and one click gets counted
      - However, since it was a direct request, DV360 will not register the click if we don't use Click Macro

### Click Macros
- A ping URL which tells DV360 about the creative and registers the click request made on third party ad server. 
- We can use any type of tag like iframe or JS, JS is preferred
  - We can check the tag at jsbin.com to see if it's working
  - Go to Advertiser in DV360, click on Creatives
    - Click on third party display tag 
    - Add name, dimensions, landing url and insert third party tag copied from Ad server (CM360)
    - Do not enable scale to fit device width 
    - It takes few minutes and then tags get verified
    - Success message: Tag recognized and click tracking macros enabled
    - You can google search for DV360 click macro and support article provides the click URL 
    - We can use test tag to verify where click tracking micro is working or not

## Native Ads and Rich Media Ads 
- Native ads are ads which serves on the website and looks like the content on the website
  - Hard to differentiate between the original and Ads
- Rich media ads are the ads where user can interact wth the Ad e.g: mute, play a game of complete the form.com
- To create rich media in DV360:
- Click on advertiser and then creatives to Click on format Gallery
  - Preview and select the recommended format like Swirl, Flipbook or Panorama
  - We can also select video specific rich media 
  - Click on any format to see the features and supported assets required
  - 