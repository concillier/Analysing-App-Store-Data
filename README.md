# Analysing-App-Store-Data
I just realised I have *36* mobile applications installed on my 64GB phone and a couple of questions ran in my mind: 
- When did I download all these apps and how many of them do I actually use? (- Is this healthy? )
- Is this the same case as everyone else
- What attracts me to download, use, buy and rate an App on the Appstore?
- Are my favorite apps the favorites of other people? 
- If not, are there any interesting sites that I am missing on?
- What are some of the most succesful apps in the world apart from the mainstream ones we know (facebook, tinder, messenger, whatsapp, instagram, linkedin)?
- Having a look at my phone's screen time analytics makes me realise that my most used apps are: Social networking, Productivity, Creativity. Is gaming thriving without me? 🤣

These and many other questions made me realise that the App store dataset is probably a dataset I would genuinely have fun exploring and getting some discoveries out of the way. With this, I went to Kaggle for some datasets and inspiration and found this: https://www.kaggle.com/ramamet4/app-store-apple-data-set-10k-apps/data


# Source of data & Acknowledgements

- The data was extracted from the iTunes Search API at the Apple Inc website. We will be digging to find out about the Mobile applications published and downloaded on App store.
- The data was extracted from the iTunes Search API at the Apple Inc website. R and linux web scraping tools were used for this study.
- Data collection date (from API): July 2017
- Dimension of the data set: 7197 rows and 16 columns

# appleStore.csv
|row | Definition |
|-----------|--------|
|id         | App ID |
|track_name | App Name |
|size_bytes | Size (in Bytes)|
|currency | Currency Type |
| price | Price amount |
| ratingcounttot | User Rating counts (for all version)|
| ratingcountver | User Rating counts (for current version) |
| user_rating | Average User Rating value (for all version)
| userratingver | Average User Rating value (for current version)|
| ver | Latest version code |
| cont_rating | Content Rating |
| prime_genre | Primary Genre |
| sup_devices.num | Number of supporting devices |
| ipadSc_urls.num | Number of screenshots showed for display |
| lang.num | Number of supported languages |
| vpp_lic | Vpp Device Based Licensing Enabled |

# appleStore_description.csv
|row | Definition |
|-----------|--------|
| id | App ID |
| track_name | Application name |
| size_bytes | Memory size (in Bytes) |
| app_desc | Application description |

# Possible questions: 
1. How does the App details contribute the user ratings?
2. Try to compare app statistics for different groups?
