# Instagram-Bot
Instagram-Bot is a program that uses Instagram for you and automatically likes certain content for you while making sure that the Instagram algorithm give you the best suggestions.

# HOW TO USE
STEP 1: RUN THE PYTHON SCRIPT
STEP 2: ENTER LOGIN CREDENTIALS
insta_username = ''  # <- enter username here
insta_password = ''  # <- enter password here
STEP 3: ENTER WHICH SECTION TO LIKE/DISLIKE AND SET THE AMOUT OF FOLLOWERS YOU WISH THE BOT TO GET/FOLLOW
# general settings
    session.set_relationship_bounds(enabled=True,
                                    delimit_by_numbers=True,
                                    max_followers=4590,
                                    min_followers=45,
                                    min_following=77)

    session.set_dont_include(["friend1", "friend2", "friend3"])
    session.set_dont_like(["pizza", "#store"])

    # activity
    session.like_by_tags(["natgeo"], amount=10)
STEP 4: ENJOY THE MAGIC AND WATCH AS INSTAGRAM USES ITSELF!!!
