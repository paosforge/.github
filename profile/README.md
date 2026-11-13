# PaOS Forge™

**A new personal operating system in development.** PaOS is being built around a native desktop, modular Linux capabilities, and useful automation and AI. The goal is a familiar day-to-day computer experience with more room for local tools and owner control. PaOS Forge™ is the project's trademarked name, used for the website and this GitHub organization.

PaOS is directed by Peter and written mostly by AI coding agents (Claude and Codex), checked by automated tests on real hardware.

> **Pre-0.1.** PaOS has been tested only on six specific machines in our lab. It is not installable on general hardware, and there are no downloads yet.

**Five ways in:**

1. **Vision, docs and videos:** [the PaOS Forge website](https://paosforge.com/), the [roadmap](https://github.com/paosforge/paos/blob/main/docs/ROADMAP.md), and [Peter’s AI theory channel on YouTube](https://www.youtube.com/@AITheory-ev2mw) (the first PaOS video is still to come).
2. **The 0.1 simulator:** [explore the PaOS 0.1 Preview desktop in your browser](https://paosforge.com/simulator/). It is a design preview of planned behavior, not the real OS; best on a laptop or desktop.
3. **The GUI preview VM:** coming. Real PaOS code in a virtual machine, running ahead of the hardware track; you link your own AI.
4. **The real code:** [`paosforge/paos`](https://github.com/paosforge/paos), a read-only source preview published as dated snapshots. For reading now; download and install come later.
5. **How to contribute:** reports, hardware notes, ideas, reviews and SDK apps by email to hello@paosforge.com. See [how to help](https://github.com/paosforge/paos/blob/main/CONTRIBUTING.md). Security problems go privately to **security@paosforge.com** (no details in the first message; we reply privately).

## What makes it different?

The release plan combines a native PaOS desktop with modular Linux guest capabilities for familiar command-line tools and selected apps. It also calls for local AI, and for typed commands (each with a fixed name and checked inputs) that scripts and AI tools can use only with the owner's permission. The [0.1 simulator](https://paosforge.com/simulator/) lets you explore this direction today; its interactions are illustrative and do not establish finished OS behavior.

## Work with the Forge

Gransee Engineering is open to discussing **scoped feasibility work** around hardware and driver interoperability, and selective embedded or appliance prototypes. A first engagement could produce a tested hardware inventory, a reproducible bring-up result, and a written account of limitations and next steps. As PaOS matures, custom workflows for small teams may become another fit; production use with sensitive data or fleets needs proven backup, access, audit, and support capabilities first.

These are exploratory project inquiries, not an announcement of PaOS commercial support or certified deployments. For a candidate project, use [Gransee Engineering's contact form](https://gransee.com/#contact) and see [PaOS Forge](https://paosforge.com/) for the product's current status.

## Security and safety by design

PaOS is being designed to keep the owner's authority above apps, guests, and AI agents. The release requirements call for Secure Boot to stay on, signed and recoverable boot and updates, limited capabilities for software and devices, and installation that preserves the existing system and data. A missing model or a mistaken AI verdict must never grant permission. Protective changes must not silently lock out the owner or destroy data. These are requirements still being tested on real hardware, not protections proved by the browser simulator. Today the core Secure Boot chain refuses tampered boot files on our six lab machines; the full try-and-install journey isn't checked yet.

## AI defending against AI

Peter's guiding idea is to use AI to protect people from hostile AI **and** conventional threats. The planned Guardian watches local security events from networks, peripherals, and agents, then helps explain suspicious behavior in plain language. Examples include a rogue agent, an untrusted USB device, a suspicious download, or a network trick. The defender does not need to out-think a larger attacking model: local context and enforceable boundaries give it a different advantage.

AI can detect, correlate, and advise, but deterministic rules enforce the boundary. Any automatic tightening is limited to predeclared, bounded, reversible, recorded responses. Loosening a safeguard or taking an irreversible action remains the owner's decision. Security events and baselines stay on the machine unless the owner approves a limited summary for sharing.

## Evidence before assurance

PaOS will call a protection ready only after independent adversarial and failure tests, including a missing or wrong model, hostile input, false positives, recovery, and supported real hardware. Releases should state what was tested and what remains unsupported. The 0.1 simulator shows the intended experience; it is not proof of native PaOS security.

## Licensing plan

PaOS uses **[MPL-2.0](https://www.mozilla.org/en-US/MPL/2.0/) for the PaOS core** (boot, Manager, kernel, PaOS-owned core drivers and hypervisor) and **[Apache-2.0](https://www.apache.org/licenses/LICENSE-2.0) for app interfaces, the SDK, the definitions of its typed commands and the Forge tools**. MPL's file-level copyleft means modified covered core files are shared when distributed. Separate apps, games, drivers, recipes and bundles may use the author's chosen license, including open or proprietary terms. Shipped Linux guests keep their own GPL and other upstream licenses and require the applicable source offer; GPL is **not** the PaOS core license.

Contributions will use DCO sign-off, with no CLA or copyright assignment. The [source preview](https://github.com/paosforge/paos) carries the license files and third-party notices. Downloads come with 0.1 Preview.

## Ways to support PaOS

You do not need to write code to help. A simple thank-you matters, and so does a tested code contribution.

**You can help today:**

- **Thanks and word of mouth.** Share the [Forge introduction](https://paosforge.com/) or the [0.1 simulator](https://paosforge.com/simulator/) with someone who might find the project useful.
- **Explore and review the simulator.** Try the planned desktop on a larger screen and note what feels promising, confusing, or missing. It is a design preview, so a simulator observation is not a claim that the native OS already works that way. Send feedback to hello@paosforge.com.

**Later, as the public project opens:**

- **Suggest a feature or workflow** and explain the user problem it solves.
- **Write a test report or an honest review.** Clear steps, the exact build and hardware, expected versus observed behavior, and screenshots or logs when safe to share are especially useful.
- **Improve the explanations.** Help with documentation, code comments, a code map, tutorials, translations, and accessibility reviews.
- **Test on your hardware** and contribute reproducible compatibility evidence once verified public builds and test instructions are available.
- **Contribute code.** Fix a bug, improve a widget or tool, build an app or driver, or propose a core change. The planned contribution path uses DCO sign-off, with no CLA or copyright assignment. AI-assisted work is welcome when a human contributor takes responsibility for provenance and testing.
- **Report security problems privately** to security@paosforge.com, with no details in the first message; we reply privately. Please do not post vulnerability details anywhere public.

**Support options are coming.** No donation, sponsorship or bounty link is live yet.

## Updates and contact

To hear when PaOS 0.1 ships, email [hello@paosforge.com](mailto:hello@paosforge.com?subject=Tell%20me%20when%200.1%20ships) with the subject "Tell me when 0.1 ships." Your address is used only for that one announcement and is never shared. Questions and ideas go to the same address. Peter reads everything; replies come weekly.

## Coming soon

The GUI preview VM, then signed downloads, a tested-hardware list, limitations and quick-start instructions with 0.1 Preview. **There is no public OS download yet;** the source preview is for reading.

PaOS Forge™ is a trademark. Each published capability will need its own evidence from tests on real hardware.
