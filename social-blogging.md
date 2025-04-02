# Social Blogging

## Description
An online social blogging site allows users to read blog posts, follow bloggers, and share their opinions through comments.

The blogging site needs to track the following information:
- **Posts**: a post is written by one blogger and has a unique slug for url naming generated from post tile
- **Bloggers**: bloggers can write and publish multiple posts and make multiple comments to share their opinions
- **Comments**: a post can have multiple comments and one comment can be a response to another comment
- **Tags**: tags are dynamic category of the posts. Any blogger can create a new tag as long as the name is not duplicated
- **Favourite List**: favourite are dedicated section only for the bloggers. Bloggers can add either a blog post or
other blogger to their favourite list and custom their blog feed based on the followed bloggers.

There two 2 types of users in the website:
1. **Reader Users** – These users can access the website without credentials. Their interactions are limited to:
   - Reading blog posts
   - Viewing and reading comments
   - Viewing blog tags
   - Browsing blogger profiles
2. **Blogger Users** – These users must authenticate via email and password. Besides all the features of readers,
bloggers have additional privileges, including:
   - Publishing new blog posts
   - Creating and assigning tags to blog posts
   - Making comments on 
   - Following other bloggers

## Use cases
### Profile
- Reader can sign up to become a blogger
- Blogger can sign in to the blogging website
- Reader/Blogger can view other blogger profile information
- Blogger can update their profile information
- Blogger can change their account password
- Blogger can verify their email address upon signing up

### Favourite
- Blogger can add another blogger into their following list
- Blogger can remove blogger from their following list
- Blogger can view all the bloggers from their following list
- Blogger can view all the posts of the following bloggers
- Blogger can add a post into their favourite list
- Blogger can remove a post from their favourite list
- Blogger can view all posts from their favourite list

### Post
- Reader/Blogger can view all published blog posts, filter by specific condition
- Blogger can create new blog post
- Blogger can edit current blog post
- Blogger can publish the blog post
- Blogger can draft the blog post to avoid incomplete blog post being published
- Blogger can add a post into their favourite list
- Blogger can remove a post from their favourite list

### Comment
- Reader/Blogger can view all comments in the blog posts
- Blogger can make a new comment
- Blogger can update their comment
- Blogger can delete their comment
- Blogger can reply to another comment

### Tag
- Readers/Bloggers can view all blog tags
- Readers/Bloggers can view all blog posts belong to a particular tag
- Blogger can create new blog tag
- Blogger can delete a tag that does not contain any blog
