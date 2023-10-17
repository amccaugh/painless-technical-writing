# What is this?
- This is a method to help you organize and write a technical paper/proposal as painlessly as possible
- The way we accomplish this is through an iterative outlining process similar to the [George Whitesides approach](https://pubs.acs.org/userimages/ContentEditor/1305035664639/Whitesides-ACS-Writing-a-Scientific-Paper.pdf).  
  - In step 1 you will be a topic-generating machine, writing down any idea/topic may need to be in the paper
  - In step 2 you will group similar ideas into approximate sections
  - In step 3 you will focus on arranging those ideas into an orderly logical argument so your outline conveys the points you want the paper to make
  - In step 4 you will convert each logical statement into full sentences
  - By step 5, your paper will be essentially already-written: you will have full sentences nicely organized in a logical flow
- A key ingredient to making this painless is to *only work on one thing at a time*.  So when you're organizing the logical argument, you are explicitly **not** working on figures, running calculations, worrying about correct grammar, etc.  This way, when you sit to work, you only have to think about a single task, and you get it done in a timely manner.
- The process works because each individual step is simple.  It's much easier to convince yourself to write when the task is straightforward like "arrange a few ideas into logical order" rather than ill-defined tasks like "write the introduction".
- Recommendations:
  - Do steps 1-3 **before** you've completed your research.  Constructing a coherent logical flow for your paper (and deciding on figures) can help immensely with guiding your research and limiting the amount of work you have to do.
  - If collaborating, do steps 1-3 together: these steps are critical to forming the basic arguments and ideas underlying your paper

# Initial setup

- Make new plaintext file / Google Doc
  - Write in plain text to avoid wasting time formatting, fighting LaTeX, etc.
- Label 3 sections: "Scratchpad", "Figures", and "Outline"
  - "Scratchpad" is where you will put ideas that don't have a home in the outline yet
  - "Figures" will hold any ideas for figures/graphics you have
  - "Outline" is where you will develop your basic outline
 
# Steps 

*The goal is to work on one single step for at least 20 mins at a time, repeatedly until the step is completed.  Resist the urge to skip ahead*

### Step 1: Generate topics that may be relevant to the paper
  - Write down any ideas/topics relevant to the paper as its own line under "Scratchpad"
    - Each line should only be a few words
    - Err on the side of capturing too many ideas/topics -- even if only somewhat related
    - Not all ideas from the scratchpad will be used in the outline, but the point is to make sure you don't forget/miss any topics later on
  - Any ideas for figures should go in "Figures"
  - Potential areas to think about when coming up with ideas:  motivation, previous work/background, theory, results, experimental setup, conclusion, equipment, fabrication, parameters, modeling, simulation, caveats

### Step 2: Group topics into rough sections
  - Look over your scratchpad ideas and try to come up with rough groupings for the topics
    - e.g. motivation, background, theory, experiment 1, experiment 2, analysis, future work
  - Cut the topics out of the "Scratchpad" section and paste them into your rough groupings
  - Continue organizing until most topics from your scratchpad have an (approximate) home
  - Place figures as their own bullet point, e.g. "- Figure: Circuit schematic of experiment"
  - If you think of new topics, add them to the scratchpad

### Step 3: Create the logical flow
*Note: Include your collaborators on this step. It is the most crucial for getting everyone to agree on the main arguments & flow of the paper*
  - In each section, try to sort the topics into a rough logical order
  - Review your scratchpad, moving any topics into the outline as needed
  - Expand each topic into very simple bullet points
    - Write "fixme" where needed e.g. "Our transistor will require (fixme 100W? calculate power) of power when implemented."
    - Use very short sentences & do not use correct grammar!
  - Repeat this step until each idea is in the right place (to ~90% surety), will require several passes through the outline
  - Continue adding to the scratchpad while doing the writing
  - Example: https://docs.google.com/document/d/1SVXOa2Tx7_3D5qbV1GMHinb16MC-tZsNUzOw43C9G7c/edit
- #### Why?
    - Short sentences are easier to quickly parse--and rearrange--than long ones
    - Any effort you put into writing well-structured/good-sounding sentences will work against you, as it will be harder to read and you may grow attached to the wording which will cause you trouble when fleshing out the outline.
    - Most of these points will likely be rewritten/reformatted as your outline evolves, so you don't want to waste effort writing sentences with good grammar
    - The point of the scratchpad is to capture any miscellaneous detail/idea that might spring to mind while you're creating the logical flow of the outline.  By adding these thoughts directly to the scratchpad, you both (1) capture them and (2) avoid diverting your attention away from the task of creating logical flow.
    - Example:
      - silicon good for making transistors
      - transistors used for digital computation
      - digital computation important to AI
      - silicon necessary for AI

### Intermission: Finish gathering data & finalize figures
- At this point, you may be missing information needed to fully complete the logical flow of the paper
- Now is the time to do extra experiments, perform analysis, do reading, etc
- Do not worry about addressing all the "fixme"s, only gathering enough information to make sure your outline makes sense logically
- #### Why?
  - In the next step you will be an English-writing machine, doing very little logical analysis or new thought.  It's crucial that your the logical flow of your outline be mostly-complete to allow you to focus on writing complete English sentences

### Step 4: Convert each bullet point into a complete thought
  - Rewrite each logical bullet point into complete sentences (~1-3 sentences)
  - Only focus on writing out full sentences, do **not** do any calculation/reading/figure-making (write "fixme" instead)
  - Avoid writing grammar/transitions between separate points, you may be reordering the points as you flesh things out
  - Goal: Each bullet point is well-written enough to be pasted into the paper without modification and have a quasi-readable paper
  - Example: https://docs.google.com/document/d/1pVV6VOanVaIH8BwYBuEermebI2L-4HI0Ljhx3w3bbak/edit
- #### Why?
    - The point of this step is to convert your shorthand statements to full, grammatically-correct sentences as painlessly as possible.
    - What is tempting is to interrupt the (hard) process of writing English in order to do (easier/more fun) analysis, making figures, background reading, etc.
    - Avoid this temptation! You will be surprised at how quickly you can bring the paper to near-complete form if you only focus on converting your logical arguments to grammatically-correct English

### Step 5: Convert the outline to a finalized draft
  - Go through all your "fixme" comments and address them
  - At this stage you should really only be adding things like transitions between sentences and tidying up the language; the paper should be mostly written already (just in bullet-point form)
    - Finished example: https://doi.org/10.1063/5.0157645

 

# Other notes:

- Once you're at step 5, before you sit down to write each time, review one previously-written paragraph very thoroughly for clarity/flow. Mark "REVIEWME" on next paragraph for next time.
- Try not to switch processes: e.g. when outlining, don’t switch to drawing figures/doing calculations
- Once draft completely written, compile list of fixmes and start cranking through them one by one
