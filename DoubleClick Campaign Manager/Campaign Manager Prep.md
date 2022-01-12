## Google Marketing Platform
- Set of products that work together to help plan, buy, measure, and optimize digital media experiences
- A unified solution for cross-channel marketing
  - Display & Videos 360 
  - Search Ads 360 
  - Analytics 360
  - Campaign Manager 360 
  - Data Studio 
  - Tag Manager 360 
  - Surveys
  - Optimize 360
- Uses:
  - Deliver faster, smart marketing
  - Gain control over investments
  - Understand audiences on a deeper level
  - Share insights across marketing teams
  - Create better experience at Scale
  - Leverage Machine learning and automation

## Get to Know Campaign Manager 360
- A trusted Ad server and measurement system 

### Benefits of CM360
- Trusted management 
- Comprehensive measurement
  - Holistic view of paid digital media and creative performance 
- Streamlined and efficient workflows
- Enhanced video solutions

### How does Ad serving work?
    - User visit the site with ad space 
    - The advertiser's ad is chosen to fill the space 
    - The advertiser's ad server supplies the best creative based on audience and contextual signals
    - The ad serves and feeds performance data back to the ad

### Campaign Manager 360: Works with other solutions
#### DV360
- Automatically sync creatives from CM360 over to DV360 for activation
- Use floodlight tags from CM360 to count conversions, optimize and build audiences for DV360
- Get programmatic performance data including cost in CM360 reporting

#### Search Ads 360
- Consolidated reporting across search and display for deeper insights around attribution, path to conversions, reach and performance

#### YouTube
- Consolidated view of media to analyze and optimize campaign performance

#### Analytics 360
- Connect paid media cost and performance data to first party audience data in Analytics 360 to get a full picture of the customer journey

#### Third party partners
- Use automated third party verification with Integral Ad Science to streamline the trafficking and tag-wrapping process


## Campaign Manager 360 Account Structure
- Account
- Advertiser
- Campaign
- Site
- Placement
- Ad
- Creative
  
### Agency Account        
- Advertiser 1
- Advertiser 2 
- Advertiser 3

### Marketer Account
- Marketer accounts may also contain multiple advertisers, but each one represents a different link of business 
  
## Campaign Components
- Placement
- Ads
- Creatives

## Six stages of campaign creation
- Create Advertiser
  - marketingplatform.google.com
  - Select Trafficking under CM360 
  - Create New Advertiser
  - Select All advertisers and then new 
  - Add Advertiser name 
    - Create two child advertiser with the same steps as above
    - Select floodlight, then configuration in left hand menu to choose **Share Advertiser**
    - Search the name or ID of a parent advertiser to share.
    - Activate the correct radio button and select 
- Create Campaign 
  - All campaigns > Click on New 
  - From Identification section, enter a campaign name. 
    - It should be specific and unique so that can be easily identified
  - From Advertiser dropdown select the correct child advertisers
  - Schedule the campaign by adding start or end dates 
  - Select the landing page by adding URL, where you want to users to land when they click on Ad

- Create Placement
  - From all campaigns tab, select the correct campaign
    - Within the campaign, choose New 
    - From the dropdown, select placement 
    - Select **Site Directory** to browse all the available sites
    - Toggle the radio button and select site 
    - Enter the placement name
    - From the compatibility dropdown, select display since these ads will be display ads on webpage
    - From Dimensions, select the size of placement
  
- Upload Creatives
    - From all campaigns tab, select the correct campaign
    - Within the campaign, choose New 
    - From the dropdown, scroll to Creatives and then Display
      - For bulk upload, choose batch upload
    - Enter the creative name 
      - Make sure to add dimensions in the name for easy identification
    - Type and compatibility : Display
    - From creative assets, select Ad assets
      - Once the creative is uploaded, CM360 automatically updates the Dimensions field
      - Check dimensions field and then save the creative

- Create ads
  - Under the campaign, select Ad and then standard 
    - To monitor ads serving from platform outside of CM360, select tracking ads like for email
  - Add name for the ad 
  - Scroll to placement assignment, select edit placement assignments and select the radio button to choose the placement we want to assign
  - Then scroll to create assignment, edit creative assignments and select the radio button to choose the creative you want to assign 
  - Save and finalize the Ads and verify that creative is assigned to correct standard Ad

- Download and send placement tags 
  - Verify that every component of campaign is listed as Active
  - From top right Tags menu, select download Tags
  - Select the placement tag we want to export and then download the file in Excel format
  - Review the tag and email to contact

## Set up the Audience strategy 
- Geo restrict the campaign
- Use Audience list to serve ads to people who ave already interacted with the website
  - Using the floodlight, create an audience list of people who have already added the items to cart or viewed it for a longer duration
- Show Ads during certain time hours when the user is active and services are available
- Based on Language or Technologies like device specific
- Adding two many targeting methods will narrow the audience in many cases
- Specify the Audience 
  - Select the correct campaign
  - From the delivery properties, set desired priority
    - High priority means serving the ad to the intended audience
  - Scroll to targeting then select Geography to reveal the relevant location targeting options
  - Choose specific area and then save the location
  
  ## Insights with the Floodlight
  - Floodlight tags allow you to track events after a user views or click on your ads. 
  - These insights show you which campaign are most effective at driving the actions you want like traffic on website or sales
  - Use Floodlight to measure the conversions and gather information 
  - Counter tags record the number of conversions associated with specific actions
    - Used for reach, brand awareness and traffic campaign
  - Sales tags measure the number of sales made or number of items purchased
    - You can also capture the total value of each sales 
    - Used for the conversions campaign
  - You can also use custom variables in the floodlight to capture information beyond the basics like visit and revenue
    - Like promo codes used, regions and product types 
  - Floodlight tags is helpful for creating the audience lists for retargeting
  - Under advertiser, go to the floodlight activities and name the floodlight
    - Enter the URL of the website 
    - Sales or counter in type
    - Transaction or sales
    - For Tag format, select Global site tag which is recommended for the easier integration
    - Enable the custom floodlight variables

## Measure campaign performance
- Use reach report to see how many new people are learning about the advertised products
- Break down the average click rate across the hours 
- With floodlight tracking, we can see the number of purchases the campaign is directly responsible for

    ### Components of report and attribution
    - Summary 
    - Report builder
    - Instant reporting
    - Attribution to find out the report on interaction of all paid media efforts served or tracked
    - Verification to get URL level reporting whether ads received views, served outside the set get target, served next to problematic content
- CM360 offers preset report templates for all reporting needs
  - Standard report provides the clicks, click rate, impressions and conversion data for given date range 
  - Floodlight report provides specific data related to the conversion
  - Reach report lets you check how many unique users the campaign engaged, through clicks or views, during a given period.
- Reports can be scheduled to send automatically on a daily or weekly basis

    ### Attribution Modules
    - It refers to set of rules that determines how to assign credit or sales and conversions to touch points 

## Get started with verification
- Prevents the fraud and fake clicks also protects the integrity of online advertising by helping marketers serve ads that are tag compliant, display correctly in brand safe locations and deliver quality as well as targeted results
  - Based on Geo
  - Viewability to measure the % of the impression
  - Based on content to flag sites where ads ran next to problematic Content
  - Based on video errors like video was mute or resized 
  - Spam filtering and fraud detection 
  - Select the campaign and then click on properties tab 
    - Enable the checkbox for ad blocking under verification section
    - From criteria section, add flagged domains or standard classifier 
  - Some feature of verification is requires to contact support representative for the enablement
  


## Plan video campaigns
- Confirm acceptable VAST(Video ad serving template) versions are a specification to be confirm when launching
- Required media asset files
- Video targeting restrictions to be confirmed from the publishers 
- Upload the highest possible specification video to CM360
- Video Ads can be served before a YouTube video, during a live steaming video or on a prominent blog post
- Two video types are:
  - In stream video (YouTube Ads)
  - In-banner video (Rich media videos served on page with JavaScript or iframe)
- CM360 transcodes uploaded video assets, which have specific requirements for file size and resolution, to various size and resolution
  