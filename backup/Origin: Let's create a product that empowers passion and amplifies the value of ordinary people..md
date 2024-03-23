# Origin

- Often, we want to do something to enrich ourselves.
- So, sometimes we enter the world of open source, sometimes we become self-media creators, some venture into community volunteering, and later...
- We find some joy in these endeavors, but can't seem to stick with them.
- Is it because we lack a clear goal? We can't help but wonder:
- Are we doing something valuable?
- Are we influencing others?
- Can we do more?
- How do we sustain ourselves without income?
- The usual approach is to negate it, so we don't get caught up, avoiding pain.

- However, some individuals with great achievements or historical pioneers have conveyed a thought:
- Doing valuable things will find someone willing to pay for it, doing what you love brings happiness and fulfillment, combining the two may lead to unwavering persistence.

- So, how do we make our passions valuable?
- Perhaps, we cannot detach from reality itself.
- Perhaps, we need to establish our own **brand**, in less commercial terms, let's call it faith? aspiration?
- This medium is the combination of our focus on reality and ourselves, and the medium for information, for ordinary people, is more about needing a pure aggregation, a carrier of thoughts and actions.
- At this stage, the medium I can think of is: **brand**; derived carriers include: **products**, **issues**, **blogs**.
- So, can I build a platform or tool that allows users to easily create their own brand, product, issue, and blog information carriers, making this process low-cost (economic & technical), effective, and realizing mutual value?

# About Positioning

> Z2Y Editor & Manager: Create everything from scratch.

1. Here, we help you quickly establish a brand information carrier: brand, product, issue, blog website. You can quickly publish your ideas, creations, and products & results to the world, let them see your value, and let the world respond to your existence.
2. Here, considering individuals are deep users of GitHub, a GitHub tool module will be developed, for developers, artists, educators, students, etc., to use GitHub conveniently and simply. I will automate some processes to make GitHub easier to use. Secondly, GitHub-related open source success is also a common success of humanity, here will introduce major communities and information media, so that software users can quickly receive information and benefit back.
3. Here is also a place where everything can be read. Any local file, online repository, any website can be collected into the to-read list. Let's make this place our lifelong learning place, from perception, to learning, to output, to creation, and record all your growth experiences.
4. Here, some games and tools are also collected, let's combine work and leisure to improve efficiency, let more time belong to passion, and let more of the future belong to our own career.
5. Regarding the task module, I didn't want to add it to the product initially. I don't want the product to generate anxiety at its source, but human greatness to a certain extent stems from anxiety about time. When the two intersect, for now, I only want to upgrade from task to plan in the initial stage. We only do summarization and archiving, analysis and correction. You are still free to be yourself. Subsequently, AI may help us manage our tasks, just like J.A.R.V.I.S., the details are not yet clear.

# Initial Feature List

> Basic Features

- [X] Login authentication & basic information loading
- [X] Overall software layout
- [X] Menu reading and interaction
- [X] Complete menu right-click file/folder creation
- [X] File preview & web preview
- [X] Shortcut key setting or modification
- [X] Local space initialization
- [X] Add logo
- [X] Complete display and management of open file tabs
- [X] File tab supports right-click menu (close all, close others)
- [X] Cache objects to database (history state)
- [X] Complete repository creation
- [X] Complete repository independent authorization
- [X] Complete repository push
- [X] Complete text editor code highlighting

> Unique Features

- [ ] Editor extension features
    - [X] Editor display supports syntax highlighting for various languages
    - [X] Current tab supports file positioning (recursive expansion of folders)
    - [ ] Editor supports text search, filename search
    - [X] Editor supports enhanced Markdown editing (https://pandao.github.io/editor.md/)
        - [ ] Clipboard or local image paste upload to generate Markdown image reference (priority)
        - [X] Common text shortcut keys add header, code block, list, table, etc. modes (priority)
        - [X] Develop immersive editing mode, full screen, callback after editing is closed
    - [ ] Editor supports syntax checking, autocomplete prompts (suggestions, AI prompts)
    - [ ] Editor enhancement (Tab automatic spaces, quotes and parentheses automatic pairing, etc.)
    - [X] New immersive editor added
    - [X] Complete file drag and drop within menu
- [ ] Account Features
    - [X] Use without logging in
    - [X] Github account management
        - [X] Complete avatar click preview GitHub
    - [ ] Complete non-GitHub account login (such as WeChat)
- [ ] Reading Center
    - [X] Everything is a file, any local file (image, PDF, text, etc.), website, entire Github repository, can be added to the to-read list
    - [X] Supports mainstream text reading experiences: PDF, Markdown, code highlighting
    - [ ] Other extensions (develop reading plug-in external expansion)
- [ ] Task Center
    - [ ] Focus on summarization, global overview (free-scrolling)
        - [X] Task panel (plan) add, edit, export, import
        - [ ] Plan archiving, analysis
        - [ ] Combine AI to assist decision-making plans and optimize unreasonable parts
    - [ ] Push forward tasks, to-do reminders as auxiliary (mainstream Todolist function)
        - [ ] Time setting, reminders, combined with system calendar
        - [ ] Various task table templates
- [ ] Extension Feature Mode
    - [ ] Project management for GitHub logged-in users
        - [X] Repository pull and file editing management
        - [X] Code submission
        - [ ] issue management
        - [ ] In-depth GitHub usage guide
        - [ ] Daily popular project recommendations - HelloGithub(https://hellogithub.com)
        - [X] User's Star browsing management (gitstars.zero2you.tech)
        - [X] View commit history of a file
        - [X] View star trend of a project
    - [ ] Local mode editor features (add multiple folders) - capability available, style to be designed
        - [X] Select local folders, preview, edit, etc. (persistent authorization issue to be addressed)
        - [ ] Local file push to remote Github project initialization
    - [ ] Tools: Recommendation and collection of third-party applications
        - [X] Complete AI assistant window (integration of entry to websites such as OpenAI) - capability available, style to be designed
        - [ ] LeetCode problem book
        - [X] Immersive code whiteboard - converted to simple editor
        - [X] Temporary task panel
        - [X] Image processing functions
        - [X] ID photo tool
    - [X] Slack off game
        - [X] Collect casual games for daily leisure (work and rest combined)
        - [ ] Support user-defined directories, sharing, and communication of casual games (sharing and communication to be addressed)
        - [ ] Add extensions, open source access, and establish an online game repository (GitHub)
- [ ] Establish software feedback mechanism using Github Issues
    - [ ] Add issue feedback entry in the app
- [ ] Complete software detail configuration page (shortcut keys, styles, etc.)

> Additional Features

- [ ] Note-taking function
    - [ ] Evaluation of any URL, local document, or file hash
    - [ ] Browse and evaluate records
    - [ ] Delete or modify evaluation records
- [ ] Social functions
    - [ ] Use issues for evaluation records, achieve the effect
    - [ ] Reply to or like operations using issues
    - [ ] Develop message center using issues
- [ ] AI dialogue and training
    - [X] Integration with Ollama, visualization of repository and dialogue management
    - [ ] Integration of prompts information list from local and online AI, support grouping + quick search input
    - [ ] Integration of AI-related personalized assistants, personality analysis, and auxiliary content generation, etc.