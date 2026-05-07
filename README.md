### Tools / Howtos that can be useful for other people:
- [seresta](https://github.com/aciliketcap/seresta): My tools for automating periodic web searches, extracting relevant data and then running analyses. I used it primarily for job search however it can be used in any use case which involves running searches on multiple websites and analysing results.
- [mitmproxy to sniff apps on your PC](https://medium.com/@aciliketcap/using-cgroups-and-mitmproxy-to-listen-to-traffic-on-your-computer-in-a-transparent-proxy-scenario-668f36cba2dd): A very old article which doesn't read too well 😅Basically you need another computer / VM / container to MITM HTTPS communication created by processes running on your Linux box. (You also need the certs obviously 😁.) However you can use `cgroups` directly which is arguably more straight-forward. Mainly useful for testing network related software.
### LLMs and agentic development:
- [Short article on a certain narrative in agentic software development](https://www.linkedin.com/posts/sinan-akpolat_latest-blog-post-from-anthropic-was-an-interesting-activity-7426591602862764033-kcXh) Why do LLM companies try to convince people that agents can work on their own on "cool" projects (like compilers, browsers, mathematical proofs etc.)? They feel challenged by something along the lines of "Can you call AI industry disruptive if it can't even disrupt itself?". But what if that narrative was actually true?

### Programming languages:
- [C Must Retire!](https://www.linkedin.com/pulse/c-must-retire-sinan-akpolat/) An article I wrote back in 2017 about moving to C alternatives (Go, modern C++, Swift and, Rust). It was more of a rant but we can see the sentiment was shared across many other developers. I moved on to other areas and didn't come back to Rust until 2025.
	- And [this is a comment](https://medium.com/@aciliketcap/like-some-other-people-who-commented-i-think-that-the-correct-thing-to-do-is-to-look-for-45d8fbaec4bb) to someone else's article (possible behind a paywall) which serves as kind of an update.
- [C# delegates and events](https://medium.com/@aciliketcap/c-delegates-and-events-baf4d48f84a): Very old article explaining delegates and event handlers in C# and how they relate to Strategy and Observer patterns.
- I'll write and add more programming languages related articles and put links here.
### Old Qt stuff:
- [cropper](https://github.com/aciliketcap/cropper): Simple image cropper
- [zlqt](https://github.com/aciliketcap/zlqt): Single page UI which translates command line parameters for a game into a visual menu
### Old kernel / systems related:
I want to get back to ez8139 and fakearp some time and make them more functional. However I haven't touched them in 10 years so no big chance.
- [Kernel Development Articles](https://medium.com/@aciliketcap/reviving-kernel-development-articles-from-2014-intro-be61a1646f35): Articles about Linux kernel module development by using QEMU VMs.
- [qemu-scripts](https://github.com/aciliketcap/qemu-scripts): Simple scripts to launch and configure QEMU VM instances for kernel development purposes
- [fakearp](https://github.com/aciliketcap/fakearp) : Educational, how to create a basic Linux eth driver. Creates a fake interface which responds to ARP requests. 
- [ez8139](https://github.com/aciliketcap/ez8139) : rtl8139 driver for educational purposes. It is kept simple to work only in x86_64 QEMU VMs with most features not implemented. Actually not even packet transfers were implemented AFAIR😅
- [scully](https://github.com/aciliketcap/scully): "Hello, world!" char driver for Linux kernel
- [conchat](https://github.com/aciliketcap/conchat): Multi-threaded server and client with UNIX sockets and pthreads. Kind of like a chat server. Again, just educational.

