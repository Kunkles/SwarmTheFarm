# Swarm the Farm

Swarm the Farm finds the receipts for your home insurance claim in your email and on Amazon, reads them for you,
and makes a neat spreadsheet and a folder of receipts to send to your insurance adjuster.

Everything happens on **your own Mac**. Your emails and receipts are not sent anywhere.

**This page shows you how to get it, one small step at a time.** Take your time. You can't break anything.

---

## What you need

You **don't** need anything technical: no extra programs, no typing commands. Swarm the Farm gets everything it
needs by itself. Just check these four things first:

1. **A newer Mac, with an "M" chip.** Click the **Apple** at the top left of your screen, then **About This Mac**.
   Next to **Chip** it should say **Apple M1**, **M2**, **M3**, **M4** (or newer).
   *If it says Intel, this Mac is too old for Swarm the Farm, sorry.*
2. **macOS Sonoma or newer.** In the same window, the big name at the top should say **Sonoma**, **Sequoia**, or
   something newer. *If it's older, update first: Apple menu › System Settings › General › Software Update.*
3. **Free space: about 10 to 30 GB.** Apple menu › **About This Mac** › **More Info…** › **Storage**. You need about
   **10 GB** free on a small Mac, up to **30 GB** on a big one. *Not enough? Empty the Trash and delete old downloads.*
4. **You can install apps.** If you're the one who set up this Mac, you can. *On a work or school Mac, you may need
   the person who looks after it.*

Also have ready:

- About **an hour**, and a good internet connection (the first setup downloads a lot).
- **Your Mac's password**: the one you type when you turn the Mac on. The Mac may ask for it once.
- Your **Gmail** password, in case Google asks you to sign in, and your **Amazon** password.

Swarm the Farm checks these things too, and tells you in plain words if something's missing.

---

## Part 1: Get Swarm the Farm

**Step 1.** Click this link: **[Download Swarm the Farm](../../releases/latest)**

**Step 2.** On the page that opens, look under the word **Assets**. Click the name that ends in **.dmg**
(it starts with `Swarm-the-Farm`).

> It will download. You might see a little arrow at the top right of your web browser. That is the download.

**Step 3.** Open your **Downloads** folder. (Click the smiling face, **Finder**, at the bottom of the screen, then
click **Downloads** on the left.)

**Step 4.** **Double-click** the file that starts with `Swarm-the-Farm`.

> A small window opens. It shows the **skulls** picture on the left and a blue **Applications** folder on the right.

**Step 5.** **Drag** the skulls picture onto the **Applications** folder: press and hold on the skulls, move it over
the folder, and let go.

**Step 6.** Open your **Applications** folder (in Finder, click **Applications** on the left).
**Double-click Swarm the Farm**.

> Your Mac might ask: *"Swarm the Farm" is an app downloaded from the Internet. Are you sure you want to open it?*
> That is normal. Click **Open**.

**Step 7.** The first time, it says *"Setting up"* for a few minutes. **Wait.** Then the **Set Up** window appears.
It has three parts, numbered **1**, **2** and **3**. The next parts of this page go through them in order.

---

## Part 2: Your claim

Look for **"1. Your claim"** at the top of the Set Up window.

- **Date of the loss:** the day of the fire, flood or storm. Click the date and type it, or use the little arrows.
  *The date it shows at first is just today's date.* An orange note stays under it until you pick the real one.
- **What happened:** a few words, like *our house burned in a wildfire*. (You can leave it empty.)
- **Your insurers:** the name of your insurance company, like *State Farm*. (Payments **from** them aren't receipts,
  so the app knows to leave them out.)
- **Your own businesses:** only if you have one. Otherwise leave it empty.

It saves by itself as you type. You'll see the word **Saved**.

> If you click **Done** without picking the date, it asks you first. Click **Pick the Date** and fill it in.
> (If you don't know the date yet, **Close Anyway** is fine: Set Up opens again next time.)

---

## Part 3: The helper that reads receipts (Ollama)

This is the longest part, and the only one that takes real waiting. Read it all the way through once before you
start. **Swarm the Farm does all of it for you when you click one button**; this part explains what you'll see, so
nothing surprises you.

### What is Ollama?

Swarm the Farm needs a free helper program called **Ollama** (say it like "oh-llama"). Ollama is the part that
"reads" the receipts, like a very fast assistant living inside your Mac. It's made by a different company, it's
free, and it's safe: Swarm the Farm checks that the download really comes from Ollama before it installs it.

Ollama needs two things: the **Ollama program** (small, about a minute to download) and the **reading models**
(big: **8 to 26 GB**, which is why this takes a while). A "model" is just the file that knows how to read.

### Before you click anything

- ☐ **Plug your Mac in** to power.
- ☐ **Keep the lid open.** If the lid closes, the Mac goes to sleep and the download stops.
- ☐ **Stay on good Wi-Fi.** Home Wi-Fi is best. A phone hotspot will be very slow and may use up your data.
- ☐ **Have 20 minutes to an hour.** It depends on your internet. You can use the Mac for other things meanwhile.
- ☐ *Optional, so the Mac doesn't fall asleep:* Apple menu › **System Settings** › **Battery** › **Options…** › turn
  on **Prevent automatic sleeping on power adapter when the display is off**. (On a Mac without a battery, it's
  **System Settings** › **Energy**.) You can turn it back off when you're done.

### Step by step

**Step 1.** In the **Set Up** window, scroll down a little to **"2. The AI that reads your receipts"**.

**Step 2.** You'll see two buttons side by side. Leave **"On this Mac (private, free)"** picked (it's blue when
picked). Don't choose *"A cloud service"*: that one is for people who pay for an AI service.

**Step 3.** Under that are three sizes: **Best**, **Balanced** and **Light**. One of them says
**"Recommended for this Mac"** in green, and it's already picked. **Leave it.** The app picked it by looking at how
much memory your Mac has.

> If you see a **red** message under the sizes, stop and read it. It tells you exactly what's wrong (like not
> enough free space). See the table further down for what to do.
> An **orange** message is only a warning. Picking the size that says *Recommended* makes it go away.

**Step 4.** Click the blue **Set Up** button.

**Step 5.** Now watch the words under the button. They change as it goes. Here's what you'll see, in order:

| The words say | What's happening | How long |
|---|---|---|
| *Installing Ollama, which runs the AI on this Mac (a 1-minute download)…* | It's downloading the Ollama program and putting it in your Applications folder. | 1 to 3 minutes |
| *Starting Ollama…* | It's turning Ollama on. | up to 1 minute |
| *Choosing the Best models…* (or Balanced, or Light) | It's getting ready to download. | a few seconds |
| *Downloading gemma4… (about 26 GB in all; this takes a while)…* | The big download. A blue bar fills up from left to right. Then a **second** name appears (it starts with *qwen3*): that's the second model, and the bar keeps going. | 15 minutes to an hour |
| **Ready**, with a green check mark | All done! | |

> **The bar looks stuck?** That's normal. It sometimes sits still for several minutes, especially near the start
> and near the end. Only worry if nothing at all has changed for **30 minutes**.

> **If the internet drops,** you'll see *The connection dropped. Picking it up where it left off…*. That's fine:
> Swarm the Farm waits a moment and carries on from where it stopped, by itself, several times. The part already
> downloaded is kept. While Set Up runs, your Mac won't go to sleep by itself (closing the lid still sleeps it), and
> you'll get a notification when it's ready.

**While it's working, you might see these. They're all normal:**

- A little **llama** picture appears at the very top of your screen, near the clock. That's Ollama, switched on.
  **Leave it there.** (On some laptops the top bar is crowded and the llama hides behind the camera notch. That's
  fine too.)
- A message in the top right corner saying **"Background Items Added"** or **"Login Items"**, about Ollama. It means
  Ollama will start by itself when you turn on your Mac. **That's good. Don't switch it off.**
- An **Ollama window** may open. You can close it with the red dot at its top left. Don't *quit* Ollama, just close
  the window.
- Your Mac may ask for **your Mac's password** so Ollama can finish setting up. Type the password you use to turn on
  your Mac, and click **OK**.

**Step 6.** When you see **Ready** with a green check mark, this part is done.

> You **can** click **Done** while it's still downloading: it keeps going in the background. But it's easier to
> leave the window open so you can see when it says **Ready**.

### How to check Ollama is on

Any time you want to check: open **Safari**, click the address bar at the top, type **localhost:11434** and press
**Return**. If the page says **"Ollama is running"**, it is. (If Safari says it can't connect, Ollama is off: open
**Applications** and double-click **Ollama**.)

### If something goes wrong

Find the words you see, then do what the right-hand side says.

| What you see | What to do |
|---|---|
| **Red:** *This Mac account isn't allowed to install apps…* | You're on an account that can't install programs. Ask the person who looks after this Mac to sign in to their own account, open Swarm the Farm, and click **Set Up** once. After that it works on your account too. |
| **Red:** *Not enough free space…* | Pick a smaller size (**Light** is the smallest), or make room: empty the **Trash** and delete old files in **Downloads**, then try again. |
| **Orange:** *…is meant for Macs with more memory…* | Pick the size that says **Recommended for this Mac**. |
| *Installing Ollama failed…* | It already tried several times by itself. Check your Wi-Fi and click **Set Up** again. If it fails again, install Ollama yourself (just below). |
| *The download isn't signed by Ollama, so it wasn't installed.* | Something went wrong with the download (often a work or hotel Wi-Fi). Try again later, on home Wi-Fi, or install Ollama yourself (just below). |
| *Ollama didn't start. Open Ollama from Applications, then try again.* | Open **Applications**, double-click **Ollama**, wait for the llama at the top of the screen, then click **Set Up** again. |
| A red message during *Downloading…* (it says the download kept stopping), or nothing has changed for 30 minutes | It already picked the download up again several times by itself. Check your Wi-Fi, then click **Set Up** again. **Nothing is lost:** it carries on from where it stopped, it doesn't start the big download over. |
| The Mac went to sleep, or the lid was closed | Open it, then click **Set Up** again. It carries on from where it stopped. |
| It says **Ready**, but later the app says it can't reach Ollama | Ollama got switched off. Open **Applications**, double-click **Ollama**. |

### Only if Set Up didn't work: install Ollama yourself

Only do this if the table above told you to. Go slowly; each step is small.

**Step 1.** Click this link: **[ollama.com/download](https://ollama.com/download)**

> **Is your Mac a little older?** Click the **Apple** at the top left of your screen, then **About This Mac**.
> If it says **M1** or **M2**, use this link instead:
> **[Ollama for M1 and M2 Macs](https://github.com/ollama/ollama/releases/download/v0.35.1/Ollama.dmg)**
> (the newest one doesn't work well on those Macs yet). It downloads straight away. Then skip to Step 3.

**Step 2.** Click the big **Download** button (it may say **Download for macOS**).

**Step 3.** Open your **Downloads** folder and **double-click** the file named **Ollama**.

> A window opens with a **llama** picture and an **Applications** folder.

**Step 4.** **Drag** the llama onto the **Applications** folder, and let go.

> If your Mac asks whether to **replace** an Ollama that's already there, click **Replace**.

**Step 5.** Open **Applications** and **double-click Ollama**.

> Your Mac asks: *Are you sure you want to open it?* Click **Open**.
> Ollama may show a welcome window. Click **Next** or **Install**. If the Mac asks for a **password**, type the
> password you use to turn on your Mac, and click **OK**.

**Step 6.** Look at the very top of your screen, near the clock. If you see a little **llama**, Ollama is on.
You can close Ollama's own window (the red dot), but don't quit it.

**Step 7.** Go back to **Swarm the Farm**. At the top of the screen click **File**, then **Set Up…**, then the blue
**Set Up** button again. This time it skips installing Ollama and goes straight to the downloads. Wait for
**Ready**.

---

## Part 4: Connect your email and Amazon

In the **Set Up** window, scroll down to **"3. Your accounts"**.

- **Gmail:** click **Connect**. Your web browser opens a Google page. Pick your email, then click **Continue** or
  **Allow**. (Google may say it *"hasn't verified this app"*: that's expected. Click **Continue**, or if you only see
  **Advanced**, click it and then **Go to Swarm the Farm**.)
  Swarm the Farm can only **read** your email. It can't send, change or delete anything.
- **Amazon:** click **Connect**. A new window opens with instructions. Click **Continue to Amazon** and sign in
  **in that window** (not your usual web browser), the way you always do. Amazon's page says *Sign in or create
  account*: type the email you already use for Amazon. Don't make a new account.
  > If a box pops up saying **No passkeys available**, click **Close**, then type your password.
  > If Amazon asks you to **make a new password**, that's normal: Amazon is being careful with a new window. Make
  > one there, then sign in with it.

  When you're in, the window says **Amazon is connected** and closes by itself, and Amazon gets a green check mark.

Then click **Done** at the bottom of the Set Up window.

---

## Part 5: A quick tour

When you click **Done**, a short tour shows you around: the window goes dark except for the part being explained.
Click **Next** to go on (or **Skip** if you'd rather explore yourself). You can see it again any time from **Help** ›
**Swarm the Farm Walkthrough**.

---

## Part 6: Find your receipts

Click the **magnifying glass** button at the top (**Find Receipts**), then click **Find**.

> It reads your email in the background. The first time can take **a few hours** if you have a lot of email.
> You can watch the progress at the bottom left. You can use the Mac for other things meanwhile.

> Need to stop? Click **Stop**, or just quit. Next time you open **Find Receipts** it asks: **Continue** (picks up
> where it stopped) or **Start Over**. Continue is already picked.

Receipts dated **before your loss** are left out of the export (utility bills from the year before are kept, because
adjusters ask for them). If one might belong anyway, like an old receipt in an email you sent after the loss, it's in
**Needs a Look** for you to decide.

To look at only some dates, use **Showing** just above the list: pick *Since the loss*, a year or a month, or
*Custom range…*. Click **✕** to see everything again.

Don't want a receipt? Right-click it and choose **Delete** (or press the Delete key). Nothing is ever thrown away:
it goes to **Deleted** in the list on the left, and **Put Back** returns it.

When it's done, click **Export** (the square with an arrow) to make the file for your insurance adjuster.

**Your insurance: the Coverages side.** At the top of the window there are two buttons: **Receipts** (everything
above) and **Coverages**. Click **Coverages** to see your insurance.

- **Your Policy.** Insurance companies often send one long booklet with every option they sell. Drag it onto
  **Your Policy**, with any endorsements and your **declarations page** (the pages that list your coverages and
  limits). Swarm the Farm keeps only the parts that are on your policy, shows your limits next to them, and warns
  you if your declarations page lists a document you haven't added. For State Farm, **Get It** next to a missing
  form downloads State Farm's standard wording of it from their website (only the form number is sent). Your
  insurance company is at the top of the page. Click **Print…** or **Save as PDF…** to keep a copy.
  *This helps you find your way around your policy. It isn't legal advice: your full policy is what counts.*
- **Payments.** The payments your insurance company has made you, read from their emails, added up by coverage (your
  house, your belongings, living expenses) next to what you've spent, and, once you've added your policy, each
  coverage's limit and what's left. Click **Find Payments in Email** to search your Gmail for the emails about your
  insurer's payments since the loss, including forwards of its letters, your adjuster's notes and the lender's
  loss-draft emails, and read the payments in them (the first time can take about an hour). Your claim number
  (Settings › Claim, filled in for you from your insurer's emails) helps it find them. Click a payment to see the
  letter with the amount in it (and the email it came in) on the right, and to change it, leave it out, or delete it (**Show Deleted**, below the
  list, brings it back). Only your insurance company's own emails count: the same payments
  retold by someone else (a forward, your adjuster, the lender) are listed as *From someone else: not counted*, so
  you can tick one if it should count. A payment your insurer canceled and sent again (a check made out wrong, say)
  counts once, as the one sent again. Tick **Hide duplicates** to hide the ones left out because they repeat another
  (the same payment in another email, an older total). You can add a check that came by mail too. (Your insurance company's name
  goes in Set Up, under *Your insurers*.) **Held back** shows what your insurer's newest letter says it's still holding
  back on a coverage (recoverable depreciation, usually paid once you replace or repair); it isn't counted as paid.
  Your house and its other structures (garage, fences, landscaping) are paid together, so they show as one group,
  **Coverage A** at State Farm. Its limit includes what your declarations page adds to it, each on its own line:
  debris removal, trees, an increased dwelling limit (Option ID), code upgrades (Option OL). Your insurer won't pay
  more than a limit, so if a coverage's payments come to more, **Left** says *Check payments*: a payment is probably
  counted twice or under the wrong coverage. With your insurer's estimate added, each part shows what the estimate
  pays on it and what's left of its limit: *Used up* (capped at its limit), or the amount still there (like code
  upgrades, paid as you incur them, or debris removal if there's more to haul away than the estimate has).
  **Add a Document From Your Insurer…** takes three kinds of document, and tells them apart: your insurer's own
  **list of its payments** (at State Farm, Claims Hub › Payments, printed to a PDF), which Swarm the Farm checks
  against the payments found in your emails (what's missing, what's extra, any canceled check) and then uses for the
  totals; a **receipt of one payment** (its letter, a check stub, or a photo of either), read for the payment; and
  its **estimate**. State Farm's Claims Hub list and estimates are read from their text, exactly; another
  insurer's layout, or a photo of a list, is read by the AI (it takes a few minutes), and its numbers are checked
  against the page: anything that doesn't add up is listed with it to look at. Below it, **Add Your Insurer's Estimate…** reads the
  estimate your insurer sent (the long one with a *Summary for…* page per part): what each part is worth, what's
  over your limits, the limits it used, and what it takes out until you've paid for it (*paid when incurred*: keep
  the receipts) or until it has more information, next to what's been paid.
  *Payments is still being tested: the amounts are read from your emails automatically and can be wrong or missing,
  so check them against your insurance company's letters.*
- **Ask about your policy.** Type a question in your own words, like *How long will it pay for a place to live?*
  The answer comes from your policy's own words, with links to the parts it used. It takes about half a minute.
  You can ask follow-up questions, and everything you ask is kept, so you can scroll back to it later.
  **Clear…** starts over. *It isn't legal advice: check the parts of your policy each answer links to.*

**More than one claim?** Click **File** › **New Project…**. Each project keeps its own receipts. Switch between them
with the folder button at the top left, or **File** › **Projects…**.

---

## Something not working?

| What you see | What to do |
|---|---|
| The Mac says it *can't be opened* | Click the **Apple** at the top left › **System Settings** › **Privacy & Security**. Scroll down and click **Open Anyway** next to the app's name, then **Open**. |
| No llama at the top of the screen | Open **Applications** and double-click **Ollama**. |
| Reading receipts is very slow, or the Mac gets hot | **File** › **Set Up…**, choose **Light**, and click **Set Up** again. |
| Google says the app is *"blocked"* or *"only for testers"* | Ask the person who sent you this app to add your email address. |
| The Set Up window comes back when you open the app | The **Date of the loss** isn't filled in yet. Fill it in (Part 2). |
| Something went wrong and you're not sure what | Click **Help** › **Report a Problem…** (or the **Report a Problem…** button next to the error). Type what happened, click **Copy**, and paste it into a reply to the email you got Swarm the Farm from. It doesn't include your emails, passwords or sign-ins. |
| Anything else | Quit Swarm the Farm (top left: **Swarm the Farm** › **Quit**) and open it again. That fixes most things. |

Swarm the Farm updates itself. When a new version is ready, it asks you; just click **Install and Restart**.

---

## Beer

Swarm the Farm is free. A small **Buy Me a Beer** window shows when the app opens: point a phone at the code if you
feel like it, or just click **Done**. Uncheck *Show this when the app opens* and it won't come back. It's always in
**Swarm the Farm** › **Buy Me a Beer…** too.

---

*This page only holds the downloads.*
