# HashTag
To put it simply HashTag is a simple file viewer / organizer that allows users assign tags to their files using a database containing a list of file checksum and assigned tags, the tags will be broadcasted using a gossip protocol to all other users to assist them in organizing their files.
### The origin of HashTag:
As a designer / photographer I always struggled with organizing lots of images and often finding the correct image for my design project from tons of images I stored on my hard drive. My attempt to create a folder for each subject and put the related images in always ended in a failure due to multi subjected images and the influx of the new images. Soon I gave up on organizing and finding a program to assist me in that task since one person will never have enough time to finish that task.
In my head I always dreamed about a scenario that all of designers come together and start tagging all of the images on internet and next time I download an image, I can already see all of the tags in the images exif info. This dream grow into the idea of an image viewer with tagging function. and soon after I got the idea of sharing our tags to save time.
Now I'm determined to bring this dream to reality and provide a service to all of graphic designers, photographers and porn image collectors around the world without judging.
### How does HashTag works:
After opening the program you can add a folder or file by `+Add folder or files` button or dragging the folder or files into the program.
HashTag will get a list of those files and calculates their checksum and adds them to the database.
then HashTag will try to get the tags assigned to that checksum from other clients using P2P.
The users can add a tag to the current list of tags shown on the right side by clicking and typing the new tag in the input shown above the list of tags.
While idle, the users can press `gossip` button to allow the client chitchat and sync their tag database with other clients.
The user can select one or more tags and HashTag will filter all of files to reveal all of the files with matching tags. also users can use `or` and `not` to refine their filtered result.
As an additional idea: To avoid tag spamming and abuse the users can register their own username and sign their tags using a private key, other users can import or ignore a specific users tags.

here's how I imagined it working
![HashTag.jpeg](https://cdn.steemitimages.com/DQmVNan97cm3gz9GRTK6YeBxTf8kmCNZnaCDGwtajeTSTep/HashTag.jpeg)
