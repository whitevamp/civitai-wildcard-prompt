# civitai-wildcard-prompt
**A massive collection of wildcards for Stable Diffusion + Dynamic Prompts extension**

**I did not creat any of the prompts in this collection.** these are prompts, that users of civitai created, what i did was scrap the civitai image API and collected all the prompts, and placed them in to text files. there is currently 83,833 Files in this collection. all credit goes to the respective users.  

## Installation

Install the Dynamic Prompts extension if you don't have it already, then clone this repo to this folder (scroll down to learn how to clone this repo):

`\stable-diffusion-webui\extensions\sd-dynamic-prompts`

Or you can download individual text files and put them in this folder (if you don't see a wildcards folder, create one):

`\stable-diffusion-webui\extensions\sd-dynamic-prompts\wildcards`

## Information on [Dynamic Prompts](https://github.com/adieyal/sd-dynamic-prompts)

Using Automatic1111's fork, you can install Dynamic Prompts from the Extensions tab (Available>Dynamic Prompts)

If you're still unsure about what this does; basically it allows you to use wildcards to randomize keywords based on what is available inside the text file. An example prompt would be something like this:

 - for a compleatly random promt use **`__civitai-prompt-*__`** 
  - or you can manually choose any number from 1-83833. here i chose civitai-prompt-1100 **`__**/civitai-prompt-1100__`**

The result would look something like this with each generation:

- **a beautiful cute (kitten girl) cyborg with white hair, (((photo realistic))), 4k, hdr, intricate, octane render, ((volumetric lighting)), sharp focus, vignette, trending on artstation, cgsociety,**  
- **(best quality, masterpiece), rockstar in concert,**

### Resources

You can find even more wildcards to use:

[sd-wildcards](https://github.com/mattjaybe/sd-wildcards)

[Wildcards for SD](https://github.com/themartiantourist/Wildcards-for-SD)

[SDGoldMine](https://rentry.org/sdgoldmine#wildcards)

ChatGPT is free (for now) and [you can sign up for it here](https://openai.com/blog/chatgpt/).

There are Windows/Linux/macOS apps available at [prompts.chat](https://prompts.chat/).


### How To Clone This Repo

To clone a repo, you'll first need to have Git installed. If you're on Windows, [you can get it here](https://gitforwindows.org/).

Then, once Dynamic Prompts is installed, navigate to this folder using Windows Explorer:

`\stable-diffusion-webui\extensions\sd-dynamic-prompts`

In Windows Explorer's address bar at the top, type in `cmd`, and a command prompt will open.  Then put this in there:

`git clone https://github.com/whitevamp/civitai-wildcard-prompt.git`

It'll quickly download the wildcards folder into the proper place. You don't have to reboot Stable Diffusion or anything, it'll work as soon as you invoke a wildcard in your prompt.

### To-Do

To enhance organization, the folders will be configured so that A1111 will only read up to 9999 files within a specific folder. This adjustment does not affect the functionality of all the files; it primarily aims to streamline the current structure, which is somewhat disorderly.
