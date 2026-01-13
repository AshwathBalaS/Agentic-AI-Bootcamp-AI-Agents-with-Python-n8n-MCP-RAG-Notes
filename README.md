# Agentic-AI-Bootcamp-AI-Agents-with-Python-n8n-MCP-RAG-Notes
This Repository contains my "Agentic AI Bootcamp: AI Agents with Python, n8n, MCP &amp; RAG" Course Notes from Udemy

**I) Introduction**

**A) A Glimpse of What Is Possible: Antigravity, n8n, Lovable & ComfyUI**

**B) Course Overview**

**C) Instructor Introduction: Arnold Oberleiter (Arnie)**




# **I) Introduction**

# **A) A Glimpse of What Is Possible: Antigravity, n8n, Lovable & ComfyUI**

Welcome to the course. And first of all, thank you. You have made the right decision. My name is Arnie, and this is the complete Agentic AI bootcamp. I want to start a little differently than usual. Normally, I start with a course overview, which we will do in the next video. I will also introduce myself more properly then. But in this video, I just want to give you a handful of demos. We will use Anti-Gravity, we will use Lovable, and we will use an addon. Of course, we will also go into coding frameworks later, as you will see after the course overview.

If you are already familiar with these low-code tools, this may not be completely new for you, and you may already understand that you can use an agent to build an AI automation. If you are completely new to AI, you may be a little blown away by the possibilities. And if you don’t understand all of this after this video, please don’t worry—we will go step by step.

In this video, we will actually not write any code ourselves. We will just use AI to do all the heavy lifting for us. So let’s dive straight into it. As I mentioned, a proper course overview will come later because the course is gigantic.

The first thing you can do is to come to the platform, and by the way, you can also just watch me. I just want to show you what’s possible with agent builders inside these tools. If you want to do this as fast as possible, you can simply press “Get Started,” create an account, and test it for free for two weeks. Later in this course, we will also install it locally and do a lot of interesting projects.

Once you have an account, the canvas will look something like this. If you are already familiar with an addon, great. If not, don’t worry, because what I want to show you now is how an AI agent will build an AI automation for us.

We can click on the AI button and describe what we want. Let’s say we want to automate our emails in Gmail. Every time a new email arrives, it should be classified by an AI model to determine whether it is a sponsorship request or not. If it’s not a sponsorship request, the email should be labeled as important. If it is a sponsorship request, another AI node should craft a reply that politely thanks the sender and explains that we do not accept sponsorships. This reply should be saved as a draft in Gmail.

After sending this out, the agent will do the work for us. This agent searches autonomously in the right documentation and figures out which nodes we need. You can see our first nodes appear: we use an Anthropic chat model, a structured output bar, or email classifier, and a generate response node. At first glance, this looks fine.

Let’s wait until everything is done. It seems we got an error, but it debugs automatically. Now we have our workflow, and hopefully, it works. We have an email trigger, so this will check every five minutes. If a new email arrives, the agent will classify it. If it’s not a sponsorship request, it will be labeled as important. If it is a sponsorship, another AI model will generate a polite “thank you, but I do not accept any offers” reply, and it will be saved as a draft.

Right now, I connect my credentials to let it run. If you don’t have credentials, don’t worry—we will cover this later in the course. Then I press “Execute Workflow.” It seems promising so far. The email got labeled as important because it was not a sponsorship request. The workflow worked completely out of the box. Congratulations! We used an AI agent to build an AI automation. If you don’t understand the terms yet, we will define them later.

Next, I want to show how a coding agent can generate another AI workflow. We’ll use Anti-Gravity for this. Anti-Gravity is a coding agent from Google. Google acquired Windsurf, and the team built something similar to Cursor. If you already know Cursor vs Code, this should be familiar. If not, don’t worry; I will teach you these tools because we will use coding agents to code really cool projects later.

For example, we can ask it to create a simple config workflow. A Stable Diffusion Excel model should generate a picture, save the workflow as a JSON file, and we can use it. This agent will think, generate a plan, and if we approve it, it executes. Convoy is a tool we can run locally to generate pictures.

You will see a task list as part of the plan. The agent shows the entire implementation plan. We can change the plan if needed, but this one seems fine. By typing “go boom,” the agent creates the workflow and saves it as Sdcl_workflows.json in the config folder.

I open the config folder, drag and drop the workflow into Convoy, and now we have the workflow ready. The prompt is included, so we should be able to generate a picture immediately. I use the appropriate model and press “Run.” The K sampler fires up, the rendering begins, and boom! There’s the picture generated completely out of the box without documentation.

Another example is using already-built agents like Lovable to create a front end for this workflow. I connect MCP access inside Lovable and ask it to build a front end for the Banana Pro LinkedIn add-in workflow. The agent browses my instance, reasons about the workflow, and generates an app that can transform images with AI magic. I upload an image, describe the changes, and get the output.

These are just some tests and examples of agents out of the box. Later, we will build agents in code, like a complete pedantic AI deep research agent. We will use Python and other frameworks to build really cool projects. This was just a glimpse of what’s possible with tools you can use out of the box.

If you are already familiar with these tools, some of this may not be new. Don’t worry—we will go into much more detail, build cooler things, and really dive deep. If you are completely new to AI, you may be amazed, but we will take it step by step. We will start with easy-to-use tools and later code interesting projects. There is something for everybody.

In the next video, we will start with a proper course overview. These were just examples—you don’t have to do them if you don’t want to. You can download the workflow I showed, get the JSON file, and import it into your canvas using “Import from File.” I call this Gmail Email Classification. If you open it, you can use it out of the box.

Later, we will build more projects not only with Anti-Gravity and Lovable but also using coding frameworks like Python, JavaScript, and many other tools. And again, in the next video, we will go through a proper course overview.

# **B) Course Overview**

# **C) Instructor Introduction: Arnold Oberleiter (Arnie)**
