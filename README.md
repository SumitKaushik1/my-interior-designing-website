# my-interior-designing-website

actual website  -->https://sumitkaushik1.github.io/my-interior-designing-website/

my referenced  website --  https://freewebsitecode.com/2022/02/22/interior-design-website-template-html-css-js-100-free/



impoortant website--https://picsvg.com/  <br>
https://www.adobe.com/in/express/feature/image/convert/svg <br>
https://www.svgviewer.dev/ <br>
https://imageresizer.com/ <br>
https://www.img2go.com/resize-image <br>
https://pinetools.com/round-corners-image <br>


free domain steps  -->
indraprasthadesginstudio.eu.org

Got it 👍 you want the flow of what actually happens when you search your domain, explained in simple everyday words.

🔎 What happens when you type your domain name

You type your domain in Google/Browser
Example: indraprasthadesignstudio.eu.org

Browser asks: “Who owns this name?”
→ Goes to EU.org (because that’s where the domain is registered).

EU.org replies: “This domain is real, and its manager is Cloudflare.”

Browser goes to Cloudflare
→ Cloudflare is the DNS manager.

It says: “This domain points to GitHub’s servers at IP 185.199.xxx.xxx.”

It also says: “Use HTTPS to keep it secure.”

Browser goes to GitHub
→ GitHub has your website files.

GitHub sends back your HTML, CSS, JS.

Cloudflare protects the connection
→ Makes sure the files are sent fast and safe.

Browser shows your site
→ Finally you see your website on screen 🎉

🌍 Simple analogy

EU.org = Phonebook → Confirms the name exists and who manages it.

Cloudflare = Receptionist → Gives the exact address and secures the call.

GitHub = The house → Has the actual stuff (your website).

Browser/Google = You making the call → You get the info back to your screen.

✅ So in one simple flow:
Browser → EU.org → Cloudflare → GitHub → Back to Browser → You see website

Do you want me to make a one-line step-by-step diagram (like arrows: You → EU.org → Cloudflare → GitHub → You) to visualize this?






+++++++++++++++++++++++++++++++++

Yes 👌 I see your screenshot clearly now.
You clicked the red “+ Add” button, and it’s showing you options like:

Connect a domain

Register a domain

WAF ruleset

Workers

Pages

R2 storage bucket

👉 The one you need is “Connect a domain”.

That is the new wording Cloudflare uses instead of “Add a site”.

✅ What to Do

Click “Connect a domain”.

A box will open where you can type your domain name.
→ Enter: indraprasthadesignstudio.eu.org 

Click Continue.

Select the Free plan.




++++++++++++++++++++++++++++++++

Got it ✅ — this screen means your domain is inside Cloudflare, but it’s still showing “Invalid nameservers” because EU.org has not yet approved your domain delegation to Cloudflare.



🔑 What you need to do:

Find your Cloudflare nameservers (they are unique for your account).

In Cloudflare → Go to your domain → Overview → You will see something like: amy.ns.cloudflare.com bob.ns.cloudflare.com 

overview in the left ip sideb bar 

++++++++++++++++++++++++++++++++
Yes 👍 you are in the right place — this is the Nameservers section in EU.org.

Here’s exactly what you need to fill:

✅ Fill like this:

Name1: liz.ns.cloudflare.com

Name2: nero.ns.cloudflare.com

(Leave all IP fields blank — Cloudflare doesn’t need them.)
(Leave Name3–Name9 empty.)

⚡ Steps:

Tick the option “server names + replies on SOA” (the middle one).

Enter only those two nameservers.

Click Submit.


++++++++++++++++++++++++++++++++

++++++++++++++++++++++++++++++++

Perfect 🚀 — this screen means EU.org has checked and confirmed your Cloudflare nameservers (liz.ns.cloudflare.com and nero.ns.cloudflare.com).

Now your request is valid ✅ and you just need to wait for EU.org staff approval (usually 1–3 working days). Once they approve, Cloudflare will automatically pick it up and the red “Invalid nameservers” warning will disappear.

++++++++++++++++++++++++++++++++++

Good question 👍

Here’s how you’ll know when EU.org approves your domain:

🔎 1. Email notification

EU.org usually sends you an email (to the address you used when registering) saying your domain request has been accepted.

Check your inbox and spam folder regularly.

🌍 2. Domain starts resolving

After approval, if you type indraprasthadesignstudio.eu.org in a browser → it will resolve to Cloudflare (even if you haven’t set GitHub yet).

Right now, it won’t open because it’s still pending.

☁️ 3. Cloudflare dashboard changes

In Cloudflare, the red “Invalid nameservers” badge will disappear.

It will show a green check ✅ and your domain will be active.

⏱️ How long does it take?

EU.org reviews manually → usually 1–3 business days.

Sometimes faster, sometimes slower (up to a week).

⚡Tip: While waiting, you can already prepare your DNS records in Cloudflare and your custom domain setting in GitHub. As soon as EU.org approves, everything will go live automatically.

👉 Do you want me to show you how to pre-configure the GitHub repo settings now, so you don’t have to wait later?