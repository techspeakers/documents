Live link: https://public.etherpad-mozilla.org/p/josh-marinacci-questions

Recording: TBD

----------------------------------------------------------------------------------

An Overview of VR/AR/MR for People in a Hurry

Josh's blog post about Meta headset: https://hacks.mozilla.org/2017/09/meta-2-ar-headset-with-firefox/
The video is AWESOME! 

EMAIL: jmarinacci@mozilla.com

Josh Marinacci - Questions for Josh (save till end of call)

- Do you do any game development?
  - A: Never been video game professional - hobbyist games
- What do you think the future of gamedev with WebVR and AR will be?
  - A: Web is good for low commitment VR experiences, where you don't want to deal with large downloads. See what's fun... Also links/link traversal will be huge
- Do you think Mobile phones will continue to be the most popular devices used for VR and AR?
  - both - mobile and HMD, it's gonna be interesting... 
- How can AR help in Healthcare, Aviation and Construction Industries?
  - it can tease / augment your perception of reality - and bring info into the computer. for healthcare - a surgeon has patient info and realtime data, but they can project the MRI on the patient. Same in aviation: Pilot has RT info as overlay. Aviation repair manual is huge - millions of pages, having 3d models digitally is a huge asset. Construction is interesting b/c -- A/R & drones crossover.... will be exciting. 
- Security Risks posed by AR, how to combat them?
  - more Privacy risk than security...  (secretly projecting) - having information in secret and many ways to abuse this. redefining Privacy for this environment will be necessary.
- You talked about Vulkan, that is not yet supported in almost most of the devices out there. Do you think it will take off and we should concentrate on it(since it natively supports parallelization)? - Rabimba
  - it will take off but we don't need to worry. ultimately it's an implementation detail. (https://www.khronos.org/vulkan/)
- What are the common pitfalls new developers fall into with VR/AR? - Mariot
  - start small, test constantly. in many devices... tools are still immature, so it will take longer than you think, A-Frame makes it easier but 
- Can you think of useful applications integrating AI and AR tech? - Viki
  - i think of AI as extra tools in the toolbox, think of the problem you're deciding to solve, and then whether speech recognition or ML will be of use... the value is in the problem/solution - like auto-translation through machine vision + smart ear buds. I think of AI as augmentation, to help human make better decisions/judgments
- What has been your favorite product that address how to physically travel longer distances, in VR, in a confined environment like a living room?
  - it's really a question of app design, it works pretty well in Vive and higher-end, but still feels unnatural. Fishing rod feels good but doesn't fit... because navigation doesn't have real world analogs. " 
- What moniker do you want us to use. WebXR or WebVR. Will WebXR bits will be merged into WebVR 2.0? "IDK" - Rabimba 
  - Let's say "MR" mixed - because we don't know what it will be yet... it's trickier than just building the API, privacy issues, webRTC lets you scan for cameras... 
- Do you want us to start evangelizing using the newer/experimental capabilities that MR proposal brings? Not sure we want to showcase them yet or not - Rabimba
  - We want to hear the use cases so we can build the right API(s) - so, not ready to evangelize yet, but let's gather info and bring it back in... so we can build the right tools...
- I heard that the Virtual Boy caused damage to people's vision, do you know if there is any truth to this? I didn't get to try one (i was 13 y.o. at the time)
  - 3d with 2d is hard, and you are tricking your eyes, so people got headaches... Be aware of physiological problems of 3D
- How does SLAM work in background? - Viki
  - (sidenote: if you still remember the talk in mozfest 16? That used slam, and has some of the maths - Rabimba. Putting the link in chat -ty )
  - got a book explaning it (https://ocw.mit.edu/courses/aeronautics-and-astronautics/16-412j-cognitive-robotics-spring-2005/projects/1aslam_blas_repo.pdf)
  - magic pixie dust/crazy math. from camera - little bits of parallax info/ internal sensors deliver info on very small changes. hardware calibration makes this more accurate. still kind of lossy, but take a while... we still need to plan for that. Web principles of graceful degradation.... 
- Are these framework (say for ex AR core) cross-platform compatible by default? - Viki (ArCore only Supported Android devices and ARKit only supported iOS- Rabimba) In that case is there any framework available out there which is cross-platform (Almost everything in the Applications: Framework slide will work I guess- Rabimba)
  - our goal is for these to become a web standard that works everywhere to expose native capabilities, comparable to how webRTC works. 
- Do you think that the rise of this industry will cause a boom in the demand on/for the GPUs ?
  - if you can parallelize your problem you gain perf and richer experiences, and will continue to suck up GPUs.  



