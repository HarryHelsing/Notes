# My Reflections and Experiments
### An chronological list of tech related musings
This list will show what I have attempted, my reflections,
as well as potential future refinements. It is intended for
myself and others who wish to see my progress, train of
thinking, and what I have been doing.  
\
*(dd/mm/yyyy)*
### 05/07/2025 - Peace? I hope
- Why have I been trying to set up WiFi for all these days?
  There is only one true answer. Ethernet.
  I see the light, it's clear to me now. WiFi is bloat.
  The cable is energy efficient, marginally, faster, and
  won't hog my bandwidth. As I am at my friend's house I am
  unable to go on the hunt for a cable today, so perhaps I
  continue working on my language learning note taking app
  so I can eventually stop procrastinating learning Italian.
- Some good tools I have heard of, Teal Deer, a straight
  forward explanaition of the 'man' aka manual pages for
  Linux. I also saw a tool where you could download ofline
  wikis such as the Arch, Gentoo, or others to be able to
  get useful information without needing to rely on web
  searching, very handy! Wikiman I believe it's called.
- So after installing wikiman I encountered some errors,
  now I came to understand that I have been missing
  depenndancies, since I installed through GitHub. A small
  realisation but the whole Linux structure is beginning to
  come sharper into focus now.
- Switching tasks now, since I am at a bottleneck regarding
  Azoth, the server laptop. I will refresh my mind as to
  where I was with the language learning app.
- Introducing my friend to github is an interesting
  experience. It makes me realise the barrier to entry
  using new technology. I forget how confusing these things
  used to be for me.
### 04/07/2025 - You Shall Not Pass
- After much faffing I've come to the conclusion that it's
  because I have used a minimal install that the wifi is
  not working. Since I haven't used the full fat version
  it's probably missing a bunch of drivers. Now I could
  faff around trying to install a driver, finding an
  ethernet cable, looking for the right driver, or instead
  I could simply install the full version of AlmaLinux and
  disable the GUI (graphical user interface).
- Perhaps if I fix this issue soon I can figure out how to
  SSH into my commputer and use it remotely.
- Multi-layered problem. I want wifi drivers. How do I get
  wifi drivers? Through the internet? Can't find an
  ethernet cable. Through the full fat version of
  AlmaLinux? It's 13gb big and the only usb drive I own is
  8gb. That is what I call a bottleneck. But! Perhaps all
  is not lost, there may be a way. I have a plug in hard
  drive, perhaps I could install the drivers and their
  dependancies on that drive, then transfer them over to
  Azoth. Interesting plan however here are some thoughts:
  Since Theseus, my main laptop, is Ubuntu/Debian based,
  I'm unsure how straight forward it would be to download drivers  for a RHEL based distro, perhaps they're the same?
  Also it has occured to be the idea of using my hard drive
  as a make shift ISO for the full fat AlmaLinux, but I
  dare not mess around with the formating of the drive.
  Now I just need to think which path is the most sensible;
  buying an ethernet cable, looking harder for an ethernet
  cable, buying a bigger USB, going through some crazy
  (probably traumatising) driver transferal process using my
  hard drive, or throwing my laptop off a building onto a
  slab of concrete.
### 03/07/2025 - Weary Wifi Wandering
- Good morning, it is quarter to six, morning coffee
  numero uno has been absorbed, the golden sun rays stream
  through my windows and it's time to fix those bloody
  unmanaged wifi drivers.
- Coffee numero duo, I'm starting to think the tech world
  has a real issue with documentation, that by the time
  developers and admins have gone through the trials and
  tribulations of actually understanding and achieving what
  they set out to do they are so exhausted and burnt out
  that to document their findings is to relive the trauma
  and oh my, we can't have that.
  I aspire to be a good documentor, to learn and refine
  this practice. Please, someone help me with these
  unmanaged wifi drivers.
- Further reflections, I think now I want to develop
  systems admin skill it's best I change my usual approach
  of change things until I get it working, to aquiring
  tools for diagnostics and understanding, so I can
  implement changes decisively without making stupid
  errors. I am still wrestling with the wifi drivers.
- Personal thought: Maybe programming isn't as difficult
  as we think it is? Perhaps we make it difficult. Among
  all the frameworks, unexplained jargon, sloppy design,
  perhaps this is where the true difficulty lies. Sure, I'm
  not saying programming is easy, it's very dense and
  layered, but it seems to be this culture of pushing
  through, ignoring the discomfort and confusion that gets
  us stuck. Yes programming is supposed to be a puzzle at
  times, but perhaps not a frustrating headache, perhaps we
  make it that.
- I need to improve my diagnostic toolbelt. I have been
  fiddling with this wifi situation in the dark and I
  really need to understand what I'm doing and the
  landscape behind it.
### 02/07/2025 - Azoth is Born
- Today I will try to set up my old computer as a server.
  I will name it Azoth after the universal solvent in
  alchemy, for its job will be to be the interface between
  all my other devices.
- Troubleshooting AlmaLinux install on old laptop. Perhaps
  trying the minimal install ISO would solve this.
- Minimal ISO did not work. I will check the compatibility
  with AlmaLinux and my hardware.
- I am trying AlmaLinux 9 instead of 10, perhaps there will
  be better support for older hardware. There still should
  be a good 7 years of security updates in that version
  presuming AlmaLinux follows Red Hat's security support
  timeline.
- AlmaLinux 9 warned me that my laptop was deprecated
  hardware. I got a kernal panic not syncing error. Time to
  try AlmaLinux 8! The journey continues.
- Success! AlmaLinux 8 installed. I am faced with the quiet
  black and white blinking of the terminal, though I am
  very comfortable in the terminal and use it frequently
  on my desktop or in a tty when needed, being confronted
  with this stark potential yet lack of direction that
  comes when working without a gui, I feel a mix of
  excitement and mild dread as it dawns on me that I will
  be living here for a long time. My new home, a black
  space where the only stars are the soft grey white
  characters that inform minimally, but clearly.
- Navigating in the dark, my first time using vi, since
  vim was not preinstalled. Quite exciting. Though after
  some research it seems the extra features provided by
  vim are not fluff, in fact they're quite useful, and as
  long as I'm comfortable switching to vi when needed, I
  see no harm in installing vim.
- Ahhh, permission issues. My main account is not in the
  sudoers file, apparently this incident will be reported.
  As I am the one running the root account it appears I
  have been reported to myself. Do not worry, I shall not
  succumb to my own bias, I can be trusted to judge these
  attempts of breaching privilege with a stern and swift
  justice.
- Frustratingly the wifi, which was working in the
  installation process now appears to have gone caput.
  After running 'nmcli device' it appears that the wifi
  is "unmanaged" whatever that means.
- I have been lead to editing network config files to get
  my wifi drivers to run. It hasn't worked yet and I find
  myself in the many halls and rooms of the Linux operating
  system. A sinking feeling in my stomach. I wonder, will
  the hallways of Linux come to an end? Will I ever truly
  know these roads? Or do these halls stretch on to
  infinity? Fractal directories opening into yet more
  directories, with their unrelenting jargon and refusal
  to explain themselves.
  As I clamber through the directories I come across
  shifty config files, offering me promises of power
  and agency over my machine, but I can tell from the
  look in their eye that I am most certainly dicing with
  death, or at the very least bizarre bugs and more
  bloody headaches trying to get things to work properly.
- Personal note: I am sulking now. I am trying to rewire
  my usual instinct to plough through until it does what I
  want but since my goal is understanding and correctness
  that would be a foolish approach. I am trying to turn
  over every stone to understand my environment. I must
  have faith that the halls are not so unending, or at
  least that the main corridors that connect these halls
  will, eventually, become familiar and homely, even if
  mystery still lurks within the further regions of the
  great Gormenghastian castle of Linux.
- Time for a break, after a few hours and several rabbit
  holes I still have not managed to install vim. Writing
  these notes is really helping discharge the extreme
  cognative frustration of simple things I'm used to just
  working suddenly and simply not.
### 01/07/2025 - Preparing the Form
- Removing keyboard, battery, and track pad from old laptop
  to make AlmaLinux server. Removing the battery helps
  reduce safety concerns and energy consumption. Removing
  the keyboard and trackpad is to force to to getting more
  comfortable in the terminal and simulate the workflow of
  being a server admin.
  I am also replacing the top of the laptop with a
  transparent plastic panel to view the internals of the
  laptop, because it looks cool, that simple!

