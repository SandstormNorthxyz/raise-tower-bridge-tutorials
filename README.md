
## Distributing Tutorials:
A link to a MakeCode editor that automatically starts in the given tutorial is as follows:

`https://makecode.microbit.org/#tutorial:https://github.com/SandstormNorthxyz/raise-tower-bridge-tutorials/task2`

Where `task2` can be replaced with the name of the `.md` (markdown) file of the tutorial you want the link to point to.

## Editing this tutorial (from MakeCode, can also be edited in any markdown editor of your choice and then committed to this repo)
First, from a new blank project in the MakeCode editor, sign in to GitHub: 

<img width="639" height="132" alt="image" src="https://github.com/user-attachments/assets/bb0ba50a-1368-4c6b-99ad-9d78a5afb425" />

Then, once signed in (no need to create a new repository if it asks you) return to the MakeCode home screen. From here, if you click the "Import" button, it will now give you the option to add a project from GitHub.

<img width="646" height="573" alt="image" src="https://github.com/user-attachments/assets/188746df-acba-407d-9d9d-287a39d256d2" />
<img width="636" height="261" alt="image" src="https://github.com/user-attachments/assets/48d081d2-50ef-4e40-9825-6ec46a4392ed" />

Click the "Your GitHub Repo" option. It'll search repositories your account has access to for ones containing valid MakeCode tutorial or extension code/markdown.

<img width="624" height="295" alt="image" src="https://github.com/user-attachments/assets/98e9d2f0-c694-44f1-b83f-6abb6105c17f" />

From inside the created project, you can then edit the markdown for all the tutorials! In the explorer sidebar on the left, you can get shareable links that open the tutorial to preview them:

<img width="331" height="156" alt="image" src="https://github.com/user-attachments/assets/5919c9c3-f519-42cc-b0a8-7eeb0f827968" />

However, this is a bit clunky, because you have to go back and forth between two tabs, and keep creating new test projects to preview the tutorial. Instead, I suggest using [the tutorial tool]([url](https://makecode.com/tutorial-tool)). Copy the *entire* markdown file you want to edit (`ctrl+a`, `ctrl+c`), paste it into the text window on the left in tutorial tool, and press the `run` button in the top-left to preview the tutorial in the window on the right. You can make as many edits to the markdown as you want and preview by pressing the run button again.

<img width="1618" height="882" alt="image" src="https://github.com/user-attachments/assets/bf8a1fd2-8311-40a0-9a18-ecda45433852" />

Once you've finished editing, copy the *entire* markdown file out of the tutorial tool window and back into the MakeCode editor window where you have the repository loaded (overwriting all the old text/code inside that markdown file).

<img width="1613" height="904" alt="image" src="https://github.com/user-attachments/assets/cfc4b697-0e4b-4306-a57a-ec1050fa89f6" />

From MakeCode, you can press the GitHub button in the bottom-left to enter the GitHub dialog. From there, you can see what changes you made (known as a "diff" for the "difference" between the current and previous version of code/markdown), write a description of what changes you've made (which is helpful for viewing change history), and then "commit" and "push" your changes (which will store them to this GitHub repository).

<img width="339" height="90" alt="image" src="https://github.com/user-attachments/assets/d1a6c6ce-9772-4aad-a0d0-7d8b7a074511" />

<img width="1447" height="867" alt="image" src="https://github.com/user-attachments/assets/cbf54fed-1212-41b0-85a3-74677c52e3ef" />

You can also use this dialog to "pull," which will update your local code with any updates from the GitHub repository (for example, if someone else worked on the code and made a commit, and you then want to fetch their changes so you can add more of your own). If you have multiple people working on a project, you should always "pull" when you start working, to fetch the latest changes that someone else made and help ensure you won't be overwriting each other's changes. However, if you both make changes to a file and then both "push," it should still be fine - as long as you edited different parts of the file, it will just "merge" the changes you both made together.

If you forget to "commit and push" before closing the tab, don't worry! Changes are still stored in that MakeCode project, within your MakeCode account, they just haven't been pushed to GitHub, and so they won't take effect for any student opening the tutorial or any collaborators who pull changes to the repository. You can see what files have changes that have not yet been synced to GitHub from the arrow icons in the explorer dialog on the left of the screen (in the example, task 1 and task 3 have unpushed changes):

<img width="319" height="430" alt="image" src="https://github.com/user-attachments/assets/3a447cc7-88f8-400a-9ec1-d6c669cbf479" />

You can also use the "share" button in the explorer to get shareable links to each tutorial, rather than manually creating links. 




## Useful Dev Resources
https://makecode.com/writing-docs/tutorials/
https://makecode.com/writing-docs/user-tutorials - information on publishing and editing tutorials
https://makecode.com/writing-docs/tutorials/control-options - contains information about "Ghost Blocks," which is (one of the ways) you control what blocks students have access to in each step
https://github.com/microsoft/pxt-tutorial-sample - example tutorial repository
https://makecode.com/tutorial-tool - MakeCode tutorial tool, you can test and preview tutorials from within this by pasting the raw text from any of the markdown (`.md`) files in

## Useful Tricks:
How to add video, through either single-line HTML code or standard markdown:
```
### <video src="https://raw.githubusercontent.com/hisi741/raise-tower-bridge-tutorial/main/video/rand_vid1.mp4" controls width="20%" muted playsinline autoplay preload="auto"></video>
### ![Random Video](youtube:65ivoafQnzw)
```

