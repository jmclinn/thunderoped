# thunderoped
######OKC Thunder Editorial Website


## Post writing instructions

Alright guys, this will be a little less straightforward than tumblr, but I've set it to auto-update so the necessity to know what's going on under the hood has dropped to zero. You do however, need to know how to use [Markdown](https://daringfireball.net/projects/markdown/basics) syntax. It's easy. It's good for you to learn stuff.

### Post Info

Before writing your content there's a few lines of data that identify the post. The title, author, etc. The data we're going to define here will be:

- layout: post
  - This will never change (unless we get into video/audio posts in the future).
- title: "&lt;title goes here>"
- date: YYYY-MM-DD HH:MM:SS
  - The 'hour' section is in military (24 hr) time.
- categories: &lt;category 1> &lt;category 2> &lt;etc>
  - This could very much change. There's a 'tag' option as well, so when we want to organize posts later we may use either categories or tags. Just put relevant info here like ... thunder recap san-antoni0 ... or whatever you deem relevant.
- author: &lt;first name>
  - This is how we'll separate who wrote what, and we can have a page listing each person's posts. Using our first names works for me.
- excerpt: "&lt;A few lines as the intro/lead in to the article that will show up on the main page>"
  - Just to keep consistency end your excerpt with ellipsis '...'
We'll probably soon have an image tied to each post so that may be included here. Instructions will be added here if that ever becomes a thing.

This intro data section will be surrounded by three dashes '---' before and after the section. So the first line of your post should be '---' and the separation between the post data and the post content should also be '---'.

### Post Content

Don't indent your first line of a new paragraph, just double space. Everything else should be straightforward. Unless, however, you're adding in links or pictures. Once again, that's outlined [here](https://daringfireball.net/projects/markdown/basics). Anything more confusing or complicated just ask me about. You can inject straight HTML into Markdown so I'll do that most times when I'm including images, links, etc.

### Adding a New Post

This would be complicated, but I've worked some magic and it's not now. You're on here so you've got your GitHub account and hopefully have access to edit the thunderoped repository under my account. You can therefore access and edit all the files that make up the site. Don't. Touch. Anything. Except the '_drafts' and '_posts' files under the gh-pages branch. To work on a draft you don't want to post yet just create a new file in the '_drafts' folder and name it with the convention 'YYYY-MM-DD-title_of-post.md'. You can also edit drafts of posts that we may be working on together. This is a way to keep everyone's drafts in the same place.

To post a draft you'll have two options. If we've worked out installing git, and connecting it to this repo on your command line then just drag the file from '_drafts' to '_posts' and use the following command-line commands.

(once inside the correct folder using `` $ cd "path/to/folder/thunderoped" ``)

    $ git pull
    $ git add .
    $ git commit -m "message of what you're doing or name of new post"
    $ git push

This will upload your draft to github and the site will autoupdate.

If we haven't gone over updating via the command line with git then you'll have to copy the entire draft, create a new file with the correct name (same naming convention as above) and then paste in the draft. Commit these changes with the green button at the bottom and the post will be uploaded to the site.

##### REMEMBER TO UPDATE THE DATE BEFORE POSTING A DRAFT THAT YOU MAY HAVE STARTED A FEW DAYS BEFORE

Thanks guys. Let me know if you have any questions. Thunder up!
