# GDC 2024 — AI Workflows 音频转写

- 来源：[`gdc-2024-ai-workflows-baseline-1080p.m4a`](gdc-2024-ai-workflows-baseline-1080p.m4a)
- 音频时长：约 35:56.821
- 音频语言：英语
- 阅读版：已将 ASR 的短语音段合并为较自然的连续段落；每段保留起止时间。
- 另附 `.srt` 字幕文件，保留更细的时间轴分段，适合导入播放器。
- 说明：这是自动语音识别稿，专有名词和个别听不清处仍可能需要对照音频复核。

---

**[00:00:09.280 – 00:00:54.880]**

Great. I am excited to talk today. I think we'll hopefully have some fun stuff to share, but my name is Kent Kersey. I am the CEO and founder of Invoke. Before we get started, can I see a show of hands? Who's heard of generative AI? Keep them up. Keep them up. keep your hands up if you're tired of hearing about generative AI. All the hands are up. Just so you guys can put them down. I think we're probably all past the hype of generative AI. We've seen what it can do. We've kind of seen behind the curtain. We no longer think that it is magic, but we're asking more thoughtful questions about what role it serves in our creative process and and what we are trying to do.

**[00:00:55.340 – 00:02:05.160]**

To give you some history on Invoke, we are one of the earliest open source interfaces for utilizing generative AI on your local machine. Before we were even a company, we were building for creatives and building for artists, trying to ask questions about how artists can get more control over the generation process, how they can incorporate this into their pipeline, rather than asking questions like, how do we replace artists? Invoke is a tool for creatives and we fundamentally believe that this tool can accelerate the creative spirit of humanity and it's something that we've been building towards. You can actually go back I think it's maybe September 2022 and see our statement of values which specifically says that we're building this for artists. So I'm excited to share a little bit about our vision for that. I'll also share a little bit about what we've seen you know game studios, VFX studios, really the industry at large, how they're incorporating this technology into their pipelines, some of the considerations that we think through when we're advising customers on incorporating these tools, what it can do, and ultimately how you can make this an effective use of your time.

**[00:02:05.840 – 00:03:15.380]**

We think that it's important to own your creative power. What I mean by that is there are a lot of AI tools that have been created that will take your data and use that to train a centralized model. Effectively, they're using you as the improvement and optimization of their tool. We believe that the important aspects of this technology are that artists and creatives are able to incorporate their style and their concepts, their characters into an AI model that they own, basically training their content into the system, creating a new visual language that they can use. that we've actually helped customers do. So you can actually take these models, train them on your assets, your IP, and if you approach that in a thoughtful way, you've built a new asset and a new tool for your team to use. We'll talk through a little bit about what that looks like and maybe the differences between a fine-tuned model and maybe what you've seen in mainstream AI. We'll also talk about how you're going to start to see this stuff get deployed into Teams. So the first thing I'll talk about is AI for mainstream.

**[00:03:15.640 – 00:04:08.160]**

What is that? What is the story that we have been told for the past year and a half? Push button, get picture, right? No longer do you have to do art. You just push button and you get picture and it's perfect, right? Well, I think everyone has played around with it. Obviously, these are a couple of the worst examples of generative AI. Midjourney is probably the most popular mainstream AI tool out there today. everyone has started to see DALI come through Bing and Microsoft Paint even has generative AI now, right? Everyone's doing it. But I think what you'll notice is that most of the time when you look at the assets that these tools generate, you start to see patterns. You start to see the same thing over and over and over again and you start to realize it's not that good, right? And if you saw a game take those assets and just throw them into the game, you'd be like, well, that game's not going to do very well.

**[00:04:08.820 – 00:04:46.300]**

It's not high quality. So when we think about how does this change for professionals, what is different about AI that's built for pros, we are incorporating that into a workflow. We are training AI models on their visual language. And what I mean by that is when you're prompting for a mainstream model, you're giving it language, most of the time it feels like you're fighting it. It doesn't really understand what you mean when you say, I want it in this style or I want this character. Most of the complaints that you get from professionals fall into two categories, control and consistency.

**[00:04:46.780 – 00:05:20.640]**

I have a lot of challenge controlling it. I have trouble getting consistency. When you train models, you are defining the language that you use in your prompts. You're saying, this is my style, this is my character, I want you to make more pictures of that. You can actually teach it almost like an apprentice. Once you've trained those models, you then define where in your process you want that to be incorporated. Is it in the middle of the process after you've drawn a sketch? Are you going to do a render in Blender or Maya and throw that into the tool to have it textured?

**[00:05:20.980 – 00:05:52.540]**

You have a lot of control about where you fit it into your process and where you want that creative control. Once you've defined those two things, you have the base model that understands your language, your IP, and you have a workflow for how you can incorporate that into the creative process, you can then deploy that to the team and use this as a tool in the creative process. This is where generative AI is going, and Voke is helping teams do this. So let's start with a use case, right? I want to reduce the time it takes to generate character concept art.

**[00:05:52.660 – 00:06:42.080]**

Why? Because I want to save time. I want to have more time to do more, make a more varied game, come up with more concepts. want to do all of that, but I want to meet the standard for quality that we've set for our creative. I don't want to just offshore this to the AI model. I don't want to farm it out. I want this to be a tool in helping me realize what I can do and what we can create as a team. And the ultimate goal for all of us is building better and more immersive games for our players. That's ultimately what all of us should be aspiring to. And if you think about the process there that I just talked about. We'll talk about kind of training models here. This is an artist that we've worked with as an advisor since the early days of Invoke. He's a relatively well-known artist. He's done work for Magic the Gathering. He has a really strong project called Angelarium.

**[00:06:42.200 – 00:07:15.260]**

His name's Peter Moorbacher, and he generates some really cool artwork. I first stumbled on his art at a Dragon Con in Atlanta maybe 10 years ago. He traded me, this is a funny story, he traded me two prints for a beer. And I still frame that and keep those up because it's one of my favorite memories from DragonCon. I got some really cool art for a beer. When you prompt mainstream AI models for Peter Moorbacher, you would imagine, based on all the stories that we've heard, that you're going to get something that has, like, perfectly captured his style, right?

**[00:07:15.320 – 00:07:56.140]**

It has stolen his style. It's perfect, right? Peter Moorbacher is one of the most prompted for artists in kind of AI image generation. He's very well known. He's got a lot of art. And so theoretically he would be the most, kind of the perfect example of stolen art. We have two images here, one from Mid Journey and one from Stable Diffusion. On the left-hand side we have Mid Journey's interpretation of this prompt. On the right-hand side we have Stable Diffusion's interpretation of this prompt. When I look at this, I do not see that. I do not see the same style. I don't really see it capturing what I thought it would generate if I was asking something for a Peter Moerbacher artwork.

**[00:07:56.760 – 00:08:28.240]**

When we trained a fine-tuned model on his assets when he worked with us and we defined that visual language and we had the high-resolution assets and IP and trained that into the model, we were able to generate this. And that took maybe six to ten seconds because we trained it, we knew how to use it, we passed in a sketch and it was able to generate that for us. That seems a lot more like his style. And even then, we're probably not taking that and throwing that directly into the final work. That's probably a piece of the process.

**[00:08:28.300 – 00:09:02.800]**

We probably composite that and overpaint on it. We treat this as a tool, a creative part of the process, not a replacement for the artist. Once we've done that, we can define the workflow. You might have artists upload a concept sketch and get back a more detailed, colorized version of that asset. We can build that in Invoke's interface. We can kind of define that workflow. And just to give some more context, Invoke is the interface that you would deploy this to the team through. We have a system that allows you to actually codify this workflow using a visual editor.

**[00:09:03.020 – 00:09:35.460]**

We are one of the earliest pioneers in generative AI and exposing a lot of controllability to the user. So we have steps in this process that we can expose that allow you to inject that control element into the image generation process. And then we can deploy that workflow in a simple UI. So once we've gone through this process of defining what we're trying to generate and how that's going to go through our pipeline, we can expose that to the team in a simple interface. Because most people don't want to learn an entirely new tool.

**[00:09:35.600 – 00:10:09.720]**

This is kind of like a big transition moment for a lot of people. We're trying to understand how we can leverage the controllability and flexibility of generative AI without retraining all of our teams on an entirely new system and a new process. I think one of the most insightful things about generative AI right now is that we're not dealing so much with a technology problem. It's not that we don't have the technology to do these magnificent, crazy things. It's that we have yet to figure out how we're going to change our processes and our workflows to incorporate them.

**[00:10:09.860 – 00:10:42.500]**

That is what we are working to figure out right now. That is what most of our clients come to us asking is we've been told 2024 is the year of generative AI. How do we do that? What is generative AI in the context of our business and how do we actually do this well in a way that respects human creativity, in a way that we can actually deploy and be successful with? So the example that I'm showing here on the screen, on the left hand side we have a prompt box, a picture that a user has uploaded of a sketch, and then a third variable which is sketch strength.

**[00:10:42.520 – 00:11:12.040]**

How much like this sketch do you want the AI to output an image with? So if it's that hundred, it's the exact sketch. If it's zero, it's going to generate something completely random. In this case, we've got a relatively decent strength and we were able to prompt for that prompt there, which I believe reads something to the effect of a hive warrior bio-organic creature, and it turned it into that asset, that piece there. Now, everybody always asks me when they look at this one specifically, you guys do 3D?

**[00:11:13.020 – 00:11:48.260]**

No, we don't. This is a 2D asset, but 3D is coming. And I think this is kind of a real thoughtful point for all of us to reflect on, which is what do the processes look like when we can take an image that we've created and potentially used in Photoshop, and we can generate 3D models with that. Are those 3D models going to be perfect? Well, I think if we've learned anything with 2D assets, the answer is clearly no. We're not going to have perfect assets on the other side. There's always going to be a place for us to take, tweak, and modify these outputs with really kind of our human creativity.

**[00:11:48.560 – 00:12:04.560]**

None of this is going to be a perfect single-shot generation. We're going to iterate and play around with these tools. We're going to composite them. We're going to modify them. We're going to make them great because they don't come out of the system with that polish. It's kind of the artists on our teams that bring that final level.

**[00:12:06.320 – 00:12:34.420]**

So demo is on the screen, which means I now move to the demo portion of this, and I just show you what this looks like in reality and what that actual process looks like. If, and this is a big if, conference Wi-Fi cooperates with me. So I am on the Invoke interface right now just to give you kind of a brief demonstration. I'm not going to talk through the entire tool, but we've been building this for a year and a half, so there's a lot of options and features, and that's part of the reason that we're building a more simplified way to deploy this.

**[00:12:34.860 – 00:13:03.880]**

But on the left-hand side, you can think of this as your ingredients list. These are all the control capabilities that you have. You have basically a thousand knobs and levers to really define what you want the AI to do. The middle piece is a viewer that allows you to kind of view the either current generation or previous generations, and we have a full gallery system for managing and deploying this across the team. That's the kind of short and sweet version. I'll move directly into the workflows piece because that's kind of the cool stuff that we just talked about and released recently.

**[00:13:04.680 – 00:14:18.760]**

So I will open up the actual complex piece first. Behind the scenes, under the hood, this is our workflow editor. And I won't bore you with technical details here, but basically this is the AI process. This is how an AI image is generated. We take a bunch of inputs, prompts, models, things like that. We connect them together and we run what's called a denoising process. Then we generate an image and we save that out. This is a relatively simple workflow, but we've seen very complicated workflows that have much more automation built into them, have a lot more controllability. And the main reason for that is when you are targeting specific generation processes in your pipeline, if you're trying to generate different types of 2D assets, maybe UI UX assets, maybe icons, maybe character portraits, whatever it happens to be, you might have a different creative process to get to that output. And rather than having to learn the tool and do that manually every single time, you can automate a lot of those things and kind of codify that as this is the sketch generation one. This is the, you know, we take a blender image and texture it one. You don't have to do all of the manual tedious stuff every single time. You've kind of made that a template that you can then deploy to the team.

**[00:14:18.960 – 00:14:49.780]**

You're probably familiar with this type of concept with a bunch of other technical art tools and creative processes, so this should feel relatively natural. But once it's been saved and deployed to the team, we can simply open up our kind of normal viewer mode, and we only expose those three variables that we care about. Obviously, you can expose more, but in this case, we have a prompt, we have an image, and we have our sketch strength. And so I've got an image here that's kind of this line art of this hooded mage.

**[00:14:49.920 – 00:15:11.380]**

I've got a prompt up here, sketch strength is 50. We'll go ahead and generate with this, but maybe I can, you all are welcome to shout when I ask this question. Does anyone have a favorite color that they'd like to see this hooded mage be generated in? So we can... Banana yellow. I have a feeling I know who you are.

**[00:15:16.340 – 00:15:45.340]**

A hooded mage in a banana yellow robe. And one thing I'm going to comment on, because I think people probably noticed this, this prompt is really long, right? This is kind of a pretty hairy prompt. One thing that we don't do, that a lot of consumer AI tools do, is we don't expand your prompt behind the scenes. So if you use consumer AI tools, what they're actually doing is they're taking your prompt, they're passing that through a large language model, and they're kind of like, what did they really mean?

**[00:15:45.560 – 00:16:10.820]**

What do they really want? How do we make that a good prompt? That actually brings a lot of legal risk to you because you have no idea what you're prompting the model for. And so most of the legal and risk teams that we talk to at large publishers that we're working with, they ask questions like, do you guys mess with the prompts at all? No, we don't. Do we have visibility into the model? Are we able to train it on our IP? Yes. Do we keep that IP? Yes. So we're able to answer a lot of those questions.

**[00:16:11.100 – 00:16:32.200]**

I say all of that because when you train a model on your style, you don't really need to do all of this prompt work that I'm doing here. I'm really kind of like bending over backwards to get this thing to generate a certain style. When you train it on a style, you can say in RStudio's style, and it will know what you mean because you've trained that visual language in. So I'll stop talking now so we can just watch the cool stuff.

**[00:16:33.700 – 00:18:04.660]**

What's going to happen now is we're sending that prompt and that workflow up to the cloud. It's running on our GPUs right now. This can be run locally on your machine. Depending on your GPU, it may go a lot slower than what we're seeing here. But right now we're watching the hooded mage in a banana yellow robe conformed to our sketch and that is being generated live. At the end of this, we'll have a new asset and that will come in right now. I think we're looking at this is a 1024 by 1024 image so now we've got kind of like our banana yellow I would say that's did a pretty good job at banana yellow it's a good color right thank you for that we've got a lot of what was in that initial sketch that we use the sketch strength of 50 and this is kind of one of the tools and techniques of artists when you're using AI you are able to set the fidelity to your sketch. Do you want the AI to have any freedom, any flexibility? You can typically get more of your kind of like creative prompt to modify that output if you give it that flexibility, but at the same time you might want it to be truer to your sketch. You might want every single detail in there. In that case you can set that up to you know 100 or 95 you know somewhere up near the top. That'll give you a lot of control. That'll give or sketch, the question's going to be, what is your process going to be when you incorporate this tool into your pipeline?

**[00:18:04.680 – 00:19:00.660]**

Are you going to do that level of sketch? Are you going to kind of more control the silhouettes? It's kind of a personal decision from an artist, where do you need control? When you have this output, if you find that you want to edit certain pieces, Invoke's tool has long been one of the more artist-forward and creative tools. We have a baked-in canvas for in-painting. this to the canvas. We can modify certain elements. I've kind of come up with a new favorite joke, so I'm going to tell it to you right now. We've all seen the sixth finger that AI generates. Our unified canvas allows you to get what you really wanted, which was seven fingers. You can add that in and generate that. So I'll do that just real quick so we can kind of take a peek at that. I'm going to drop this over. I'm copying our prompt. And basically Basically what I'm able to do is I'm able to focus the AI image generation process on certain regions.

**[00:19:01.100 – 00:19:49.140]**

I'm able to select and mask. I also have the ability to brush over. If I wanted to, I could kind of go in and draw new elements with brushes and have the AI reinterpret those. So I'm basically able to iterate very quickly. It's not a one-stop shop where I put a picture in, I get a push button, get picture. It's an iterative process that I have a lot of control over as a creative. So I'm going to go ahead and zoom in real quick, and we'll see this guy's face. It looks like it could use some details there. And we're going to set our strength here somewhat low, so that it's just kind of reimagining this. And then I'm going to invoke. And what that's going to do is it's going to take this region that I've masked. Maybe I'll... yeah, we'll see that go up. It's going to take that region that I masked, it's going to regenerate just that piece, and and then it's gonna composite that back in.

**[00:19:49.600 – 00:20:18.020]**

We have the ability to do that at larger resolutions and then jam a lot of that detail back in. So what I've done is I've generated this at a very large size and I'm incorporating all of that detail the model has generated by zooming that back in and kind of pasting it in. So I've got a much more kind of high fidelity, more detailed face than my original one, which if I preview was that. It was a little bit kind of grungy, a little bit distant. So I've gotten a lot more detail in this process and it looks a little bit more like what I was hoping for.

**[00:20:18.280 – 00:20:43.180]**

So this process is one that is iterative. It is not push button, get picture. It is very much a creative workflow. And it's one that artists as they incorporate into the pipeline have said things to me like something that took me a couple of days just took me a couple of hours because I was able to go back and forth with the AI and really get to where I needed to go. And that's not because he pushed a button, got a picture and said that's done. It's because he used this as part of his pipeline.

**[00:20:43.480 – 00:21:05.100]**

He's bringing it over into Photoshop. He was compositing, he was taking sections and generating pieces for the background. He was doing this in a way that was very intentional, very much aligned with his creative vision, but he's using AI to accelerate some of those pieces. And that's what Invoke is really built for. We were built for the creative and built for that process. So I'll switch back to our presentation.

**[00:21:06.400 – 00:21:41.440]**

Workflows that we assist with, that we see people using today. Concept exploration and ideation. asset textures so you can take a blender rendering out or any 3ds tool you take the viewport and you can use that to control the generation what the generation will then do is create kind of a textured version of that asset that you just pulled out well when you have that you can push that back in and project that over to get a base texture right so you've now jump-started the texturing process and you can go and you know paint the service and do all the fun stuff that you would otherwise but it gets you a good starting point you have to start from scratch.

**[00:21:41.640 – 00:22:15.460]**

You can do seamless tiling and textures, generate those with the tool. We see 2D visual assets, ability icons, portraits, marketing materials, interface elements. We did a session last week on UI UX and the heads up display. We generated some of those components. Really, the thing to take away from this is when you teach an AI to generate a certain type of image, it's going to be able to generate that type of image. And so the question you have to ask yourself is, what do we need to generate? What should we train a model to do?

**[00:22:15.560 – 00:23:32.620]**

And how do we train it in such a way that it's a useful tool for us? And once you've built that early on in the pipeline and it's helped you out there, you now have an asset that you can actually use on the back end for marketing. You can give that to the marketing team. They can use that in creating marketing materials and creating a lot of the things that they'll use. And soon, we anticipate that you'll be able to do even more. I mentioned earlier that people ask about 3D. Well, 3D's coming. The way that that, again, works is most of the technology that's being built right now is testing this process. If you pass in a 2D image and it creates the 3D model, it kind of imagines what that might look like from a 3D perspective in an orbital view and it kind of creates that base texture. Technically, we have the technology now to do it. The meshes just kind of suck and we're working on getting there. Now, I'm going to tell you my estimate, I don't really know if this is true or not, but I've been in AI time now long enough that I feel like I've got a pulse on what's happening. I would say six to twelve months we'll probably see a really good image to 3D model. We're also starting to see image to video models, right? So you're able to, I think everybody probably collectively lost their minds over Sora for about 24 hours when it came out. We're all sharing it wildly on LinkedIn. Have you seen this? And that's coming.

**[00:23:33.460 – 00:24:41.980]**

They're going to be releasing that later this year. And you start to imagine what a movie looks like created with this stuff when you have that type of control. But I think it comes back down to when you look at where this is all going, it's using these in the creative process. It's really just accelerating that pipeline and it's changing things, but maybe not completely overhauling it to the point where we no longer need anybody in the room to do work, right? This is just changing the type of work that we do, it's changing the workflow, but we are still creative people and we are still incorporated in this process and very much needed. I'm gonna leave you all with this kind of quote that I heard, or I read this in a blog post, is from an illustrator's name Dan Luvisi. He posted this in 2014 reflecting on the 2000s. He was, you know, studying art. And he basically said, I had art teachers that hated me in high school and junior high because I would come to class while everyone else was doing pencil and traditional media. I had a Wacom tablet, crappy little Wacom tablet. And I would come in and I would use that. And it's not that the school wasn't supportive of it. They had computer labs.

**[00:24:41.980 – 00:25:09.820]**

They were trying to be STEM and teach people that. But the teachers hated them because they thought Photoshop was for hacks. They thought it wasn't real art. They basically said, hey, you've got an undo button. I had to learn art without an undo button. You don't get to qualify as an artist, because you have undo. You have brushes. You got brush packs. It's not technique. It's not craft. I think now we see probably that's maybe a short-sighted, myopic view. There's a lot of craft that goes into digital art.

**[00:25:10.620 – 00:25:41.440]**

And he leaves with this quote of, there was so much hostility against an art form that it made me begin to realize that it wasn't due to not wanting to learn it, but that it was making it easier than what they once had to use. And that is where we're at again. We have new technology. We have the next thing. And rather than look at it as a threat to us, we can look at it as a tool. The next tool, something that we still have to learn to use, something that is different than what we did before, but one that very much respects the human creative and gives us more and better ways to create games.

**[00:25:41.680 – 00:26:21.860]**

So I'll leave it with that. I think I've got some time for questions. We've got questions in the audience. There's a microphone right there. required to stand up and speak your question and I will do my best to answer it. So if anyone's interested, yeah, please get up, feel free to reach out. I'll maybe switch this to the boring screen. Cool, great talk. Thank you. Totally where I also see AI going and how we want to use it. I had a question about the how you train it on your art style. Is that like a hands-on thing or is that like here's a bunch of assets, go learn what you can learn about it.

**[00:26:21.880 – 00:26:55.920]**

We can do both. Okay. So I mentioned earlier that we are an open source team and product. You can go to our website, download everything that I just showed you to your local machine and use it for free. So if you're an individual artist right now that wants to learn what's new, you can download us for free and learn it, play around with it. There's no cost. You just have to have a little bit of a nice GPU to run it. But most of us are gamers, right? so we'll be fine. But our training process is basically one that has multiple options.

**[00:26:56.280 – 00:27:12.200]**

Our training scripts are open source as well, so if you have a GPU you can train your own model. What that entails is creating the data set so you have however many assets that you have that you want to train it into the model with. It's kind of a little bit of an art of its own.

**[00:27:13.460 – 00:27:46.240]**

A question that I've gotten a lot is how many do I need? What is enough? And it depends. If you're training a character or a concept like a vehicle, something around 30 to 50 will train that into the model. You'll be able to technically prompt for that. So we talked with a, this was like a little bit of a weird customer, but we talked with one that was working in the government, and they were doing a bunch of pitch decks for grants. We need to generate exact pictures of our drone. And it can't be just a drone.

**[00:27:46.400 – 00:28:17.380]**

It needs to be this drone because we're pitching engineers. So you're able to teach an AI model things down to that level and say, I want that drone. Not just a drone. I want that one. That's about 25 to 50. If you're doing a style, typically we recommend something around 100 to 150. It gives you more variability and flexibility when you're using that. But effectively what you do is you create that data set. you describe what's in all of those images, and you're teaching it, using those descriptions, the commonality.

**[00:28:17.820 – 00:28:56.720]**

This, all 150 of these are in our style, right? Whatever name you want to give that. And then when you prompt for that, now when you prompt for our style, it's like, oh, I remember those pictures. This is what our style looks like. So you then combine that with your sketches, your kind of control piece, and you have a really good way of getting your style in a controllable way. Awesome. Thank you. Yeah, absolutely. And we do also do professional services. We're building a, on our hosted product, building that in a web app as well. So you can just shunt us 3,000 pictures and say go figure it out and we'll help you do that. But it'll be more expensive than you downloading the open source scripts and figuring it out yourself.

**[00:28:57.020 – 00:29:35.160]**

Cool. Thanks. Yeah, you bet. Thanks. Great talk. I was just wondering about, I came in a little bit late, sorry about that. No worries. I answered your question at a very big age. I was wondering about the, well, one of the questions is do you have like a community where you can share models, train models? And also how do you work around the fact that people might be using scraped art? Yeah, so I mean I think one of the ways to think about this is there are base models that have different training sets, right?

**[00:29:35.160 – 00:30:34.680]**

So there are the kind of wide scraped data sets that we showed earlier mid journey and stable diffusion I think we could probably debate whether they effectively capture the style of anyone based on the example I showed But if you're not comfortable using those base models There are base models that have been trained on licensed assets from like Getty images and Bato and all of those Those require a license you just have to pay for that but they'll give you the model file and then you can train on that and use that in our tool. So they're effectively the same architecture is the way to think about it. It's like the same it's like a USB-C adapter for models if you want to think about it like that. It's like the same architecture but they just have different training sets so you can use whichever you want. As far as a community of models there certainly are online communities. There are ones that are less savory that we don't affiliate with. The ones that most people who are playing around with this technology in the open source space are using are on Hugging Face is kind of a machine learning solution.

**[00:30:35.180 – 00:31:11.140]**

You can't necessarily guarantee that any of those are commercially friendly depending on what you want in the training set. It's one of the reasons why you might train your own. But people are sharing a lot of those online today. Are you guys concerned about any of the kind of legality that's kind of being conversed? I spend way, way too much time in like reading laws and licenses and stuff like that. I have a lot of perspectives on copyright law. I think there are, unfortunately, either way it goes is probably not what most people want to hear.

**[00:31:11.600 – 00:31:59.480]**

But the copyright law question is one that is pretty complicated. Most of our customers have looked at it. And I think the way that it's going, as far as what we've heard from legal scholars, the way that we've heard from the litigators that are working on it, most of them believe that training is going to be a fair use activity, which means you can train on anything, which will change the nature of the internet. What we'll start to see, my prediction, will be that most of the terms of service, I think we've already started to see this, but most of the terms of service when you go to a website will start to say, like, you must agree to this before you see anything. And in those terms, it's going to say you will not train in AI. So it's moving to contract law rather than copyright law. That doesn't necessarily solve the old scraping problem but it does prevent future scraping problems.

**[00:31:59.680 – 00:32:50.340]**

The models that we use are the open source models. They do include wide internet data but they respected artists opt outs and robots.txt. So basically on any website you can put up a robots.txt, you can go to a form and kind of fill out don't include my name and that has been stripped out of the data set that went into that most recent model. We're kind of constantly trying to push it more and more towards clean data set that's openly licensed. We think it's pretty important that everybody has a good base model because in a competitive world we think everyone should have access to this, one of the reasons why we're open source. So if you have an openly licensed base model that's clean, that's the ideal, and that's kind of what we're aspiring to get to. I would say over the last year and a half we've made a lot of progress in the ecosystem of getting there.

**[00:32:50.800 – 00:33:26.760]**

Awesome. Thank you. Yeah, you bet. Take care. Thank you for the great session. Because I've seen the node editor in InVoke, I just want to ask how, to what extent does it overlap or similar with Comfy UI? Because you are both, I just understand you are also open source, and then I just want to understand. It seems like, of course, InVoke is easier to use for artists, but I want to listen to your idea about it. Yeah, so we know Comfy. We also know Automatic 11.11. Those are kind of like the two other players in the space, we've been part of that ecosystem since the very beginning.

**[00:33:27.420 – 00:34:00.560]**

The reason why you might not hear about invoke as much on like stable diffusion reddit or online, we made a pretty hard stance early on against using non-commercial code. So in Comfy UI you'll actually see a lot of nodes that are non-commercial. People are doing things like face swapping, deepfake stuff, and it's basically where a a lot of that open source technology, it's kind of like what's driving Comfy UI. We don't put non-commercial code in our open source repo. Our open source repo is also Apache 2 license, it's not AGPL.

**[00:34:00.860 – 00:35:13.620]**

So when you get into the mechanics of open source, you want to make sure that you don't have non-commercial code or models in the process. You don't really have that guarantee with any of the other open source. Ours is kind of like commercial friendly, which means we don't have really cool features like swap your friend's face into your like beach photo, but you know we're not really trying to solve that problem. When you think about invoke, we do have custom nodes. You can put that kind of level of flexibility and capability into the tool. So you have all of the creative power that you would get for most of the professional use cases that you want to see. Okay, thank you so much. Another, I think another difference is that Comfy is also support for API call or other like procedure workflow not only for artists but for other like producers or game designers like for me but it does like do you think Invoke is mostly focused for the artist or do you think it also cannot become an engine for for like multi-modal use of the AI? Yeah so we don't have an API on our hosted product but our local product does have an API that you connect into is effectively what the front end is doing, you will eventually be able to invoke specific workflows, right?

**[00:35:13.760 – 00:35:45.280]**

So we have a workflow library. We keep track of all of that. When you're building that at scale, you'll be able to hit an API and kind of invoke that specific workflow and get that done. So eventually we will have that, but we're building this in a scalable way, and that takes a little bit more time than, you know, the open source kind of hacky API that most people are building up. Okay. Thank you so much. Yeah, you bet. So we need to wrap up here, but we can still keep talking at the wrap-up room across the hall. Yeah, sounds great So we're gonna wrap up over there if you guys have questions. Thank you for coming
