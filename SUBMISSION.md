# Hackathon submission text

## High-level summary
Abandoned but not Forgotten is an interactive web museum that tells the stories of the machines NASA left behind on the Moon, on Mars and in deep space. Visitors enter a cinematic landing page, then follow a 12-scene story narrated in a human voice, where machines such as the Apollo 11 lander, Surveyor 3, Spirit, Opportunity and Ingenuity speak in the first person. A Ghost Hardware Map lets them tap glowing dots on the Moon and Mars to hear how each machine worked, what it found and how its story ended. An archive of 13 missions adds photos, key details, eight technical specs and a quiz for each mission at three reading levels (ages 0-5, 6-10 and 11-16).

How it addresses the challenge: school-age students mostly hear about active missions. This project turns the histories of dormant hardware into narrative, shows how each machine operated, and connects the engineering to the science it made possible (for example, Surveyor 3 showed the Moon's soil could hold a lander before Apollo landed; Spirit and Opportunity found evidence that water once shaped Mars; Ingenuity made the first powered flight on another planet).

Why it matters: these machines are the foundation of today's exploration. Giving them a voice builds a personal connection and inspires the next generation of scientists and engineers.

## Additional details
**What it does:** a landing page with a looping galaxy video; a 12-scene story mode with recorded narration; an interactive Moon and Mars map of left-behind hardware; a scroll-driven timeline (1967 to 2021); an archive of 13 missions with filters for Moon, Mars and Deep space; per-mission quizzes.

**How it works:** one static HTML file with vanilla JavaScript. Missions, scenes and map pins are data arrays that the page turns into the interface. Map dots are placed from real latitude and longitude. Each scene plays its own audio file. If an online NASA image fails to load, the page draws its own illustration of the machine instead. The page works from any web host with no server or build step.

**Benefits:** free and open to everyone; works on phones; keyboard accessible; reduced-motion support; reading levels for different ages; facts linked to NASA sources.

**What we hope to achieve:** make forgotten robotic explorers feel personal, give teachers a ready classroom resource, and inspire curiosity about the science these machines made possible.

**Tools used:** HTML5, CSS3 (grid, flexbox, custom properties, keyframe animation), vanilla JavaScript (ES6), HTML Canvas, IntersectionObserver, HTML audio and video; Google Fonts (Orbitron, IBM Plex Mono, Space Grotesk); ElevenLabs for the narration voice; FFmpeg for compressing audio and video; Python with Pillow for resizing images; Playwright with Chromium for testing; GitHub for hosting the code; GoDaddy for the domain or hosting; NASA Science, NSSDCA, the Apollo Lunar Surface Journal and the NASA Image Library for facts and images; Claude (Anthropic's AI assistant) for coding help (check the hackathon's rules on AI disclosure). **Hardware:** a standard laptop, no special equipment.
