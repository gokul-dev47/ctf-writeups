CTF Writeups

Writeups from CTF challenges I've solved — mostly TryHackMe rooms, picoCTF, and a few live college/national events. I started documenting these mainly for my own reference, but figured they might help someone stuck on the same problem.

I'm not going for full walkthroughs with every screenshot — the goal is to show the actual thought process: what I noticed, what I tried that didn't work, and what eventually got the flag.

Background

I've been doing this for a while now (30+ challenges solved across a few platforms), and in 2026 I  won Cyber Catalyst, a national-level CTF hosted by Veltech University, Avadi. That's probably the writeup worth reading first if you're browsing this repo for the first time.

I'm strongest in web exploitation and network/pwn challenges, but forensics and reverse engineering show up here too — those are still areas I'm actively getting better at, so expect some of those writeups to be rougher than the web ones.

Structure

Each writeup lives in its own folder, named after the event or platform it came from:

ctf-writeups/
├── cyber-catalyst-2025/
├── tryhackme/
│   ├── room-name/
├── picoctf/
│   ├── challenge-name/
└── ...

Inside each folder you'll usually find:

README.md — the actual writeup
any scripts I used (exploit code, parsers, whatever got the job done)
supporting files where relevant (not raw challenge files I don't have rights to redistribute)
Categories
Category	Notes
Web Exploitation	SQLi, auth bypass, IDOR, basic API abuse — my strongest area
Network / Pwn	Packet analysis, basic binary exploitation
Forensics	Memory/disk artifacts, file carving, log analysis
Reverse Engineering	Still building depth here, mostly beginner-to-intermediate challenges
A note on the writeups

I don't post flags directly and I try not to spoil challenges that are still active on public platforms (TryHackMe rooms especially — if a room is still live, I'll either hold off or keep the writeup high-level). Anything from closed/retired events is written up in full.

If you spot a mistake in my reasoning or a cleaner way to solve something, open an issue. I'd genuinely rather know than have it sit there wrong.

Contact

Reach out if you want to compare notes on a challenge or just talk security — details on my profile.
