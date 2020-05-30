# hugo-boss
Just checking out hugo static site generator with github pages.

Love it so far.  Very fast, seems flexible, easy to build site or blog.
Themes are kind of a pain, mainly finding a good one.  Still looking for one I like.

# Setup
To setup on a new workstation:
1. Install hugo and verify install
   
    ```
    > brew install hugo
    > hugo version
    ```
2. To build and compile the static site, run hugo (build is extremely fast)

    ```
    > hugo
    ```

    ```` 
                    | EN  
    -------------------+-----
    Pages            | 10  
    Paginator pages  |  0  
    Non-page files   |  0  
    Static files     |  0  
    Processed images |  0  
    Aliases          |  3  
    Sitemaps         |  1  
    Cleaned          |  0  

    Total in 40 ms
    ```

3. To view the site:

    ```
    hugo serve
    ```
    Open your browser to http://localhost:1313 to view the site
    
    > :bulb: Add -D option if you want to see draft posts, hidden by default.


# Add a post
To add a new post, you can use the hugo cli:

1. Use the hugo cli to add a new post.

    ```   
    >hugo new posts/my-new-post.md
    ```

    This will create a new markdown file in the posts directory with the 

2. Edit the markdown file in the posts subdirectory.  The "front-matter" at the top drives the metadata about the post.  The body is pure markdown. When hugo builds the site, these posts are converted to html posts.  
   
3. If the server is still running, the watch process will display
   
# Publish to github pages
3. When


