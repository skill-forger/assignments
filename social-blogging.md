# Social Blogging

## Description
An online social blogging site allows users to read blog posts, follow bloggers, and share their opinions through comments.

The blogging site needs to track the following information:
- **Posts**: a post is written by one blogger and has a unique slug for url naming generated from post tile
- **Bloggers**: bloggers can write and publish multiple posts and make comments to share their opinions
- **Comments**: a post can have no or many comments and only one level of comments
- **Tags**: tags are dynamic category of the posts. Any blogger can create a new tag as long as the name is not duplicated
- **Favourite List**: favourite are dedicated section only for the bloggers. Bloggers can add either a blog post or
other blogger to their favourite list and custom their blog feed based on the followed bloggers.

There two 2 types of users in the website:
1. **Reader Users** – These users can access the website without credentials. Their interactions are limited to:
   - Reading all published blog posts
   - Viewing and reading comments
   - Viewing blog tags
   - Browsing blogger profiles
2. **Blogger Users** – These users must authenticate via email and password. Besides all the features of readers,
bloggers have additional privileges, including:
   - Publishing new blog posts
   - Creating and assigning tags to blog posts
   - Making comments on blog posts
   - Following other bloggers and add blog post to favourite list

## Use cases
### Profile
- Reader can sign up to become a blogger
- Blogger can sign in to the blogging website
- Reader/Blogger can view other blogger profile information
- Blogger can update the profile information
- Blogger can change the account password
- Blogger can view all the posts belong to the blogger with pagination; filter by status, tags and blog title

### Favourite
- Blogger can add another blogger into their following list
- Blogger can remove blogger from their following list
- Blogger can view all the bloggers from their following list with pagination
- Blogger can view all the posts of the following bloggers with pagination
- Blogger can add a post into their favourite list
- Blogger can remove a post from their favourite list
- Blogger can view all posts from their favourite bloggers with pagination

### Post
- Reader/Blogger can view all published blog posts with pagination; filter by authors, tags and blog title
- Blogger can create new blog post
- Blogger can edit their blog post
- Blogger can publish their blog post
- Blogger can draft their blog post to avoid incomplete blog post being published

### Comment
- Reader/Blogger can view all comments in the blog posts
- Blogger can make a new comment
- Blogger can update their comment
- Blogger can delete their comment

### Tag
- Readers/Bloggers can view all blog tags with pagination; filter by tag name
- Readers/Bloggers can view all blog posts with pagination belong to a particular tag
- Blogger can create new blog tag as long as the tag name is not duplicated
- Blogger can delete a tag that does not contain any blog

## Extra Use Cases (optional)
- Blogger can verify their email account upon signing up via OTP code or verification URL
- Blogger can see all the input validation error upon creating blogs
- Blogger can reply to another comment with only 1 level of response
- Blogger can reply to another comment without any limitation in level of response