# PaOS Forge™

**A new personal operating system in development.** PaOS Forge is being built around a native desktop, modular Linux capabilities, and useful automation and AI. The goal is a familiar day-to-day computer experience with more room for local tools and owner control.

- [Explore the beta desktop simulator](https://gransee.com/review/paos-8bc176296315f468b1089ab1/) — a browser design preview of planned windows, apps, themes, and workflows; best on a laptop or desktop.
- [Visit the PaOS Forge website](https://paosforge.com/) — the project introduction and current status.
- [Follow Peter’s AI theory channel on YouTube](https://www.youtube.com/@AITheory-ev2mw) — a plain-language PaOS introduction is planned, about busy lives, AI-assisted building, and making more time for people.

## What makes it different?

The release plan combines a native PaOS desktop with modular Linux guest capabilities for familiar command-line tools and selected apps. It also calls for local AI and typed automation with explicit owner-control boundaries. The browser simulator lets you explore this direction today; its interactions are illustrative and do not establish finished OS behavior.

## Work with the Forge

Gransee Engineering is open to discussing **scoped feasibility work** around hardware and driver interoperability, and selective embedded or appliance prototypes. A first engagement could produce a tested hardware inventory, a reproducible bring-up result, and a written account of limitations and next steps. As PaOS matures, custom workflows for small teams may become another fit; production use with sensitive data or fleets needs proven backup, access, audit, and support capabilities first.

These are exploratory project inquiries, not an announcement of PaOS commercial support or certified deployments. For a candidate project, use [Gransee Engineering's contact form](https://gransee.com/#contact) and see [PaOS Forge](https://paosforge.com/) for the product's current status.

## Security and safety by design

PaOS is being designed to keep the owner's authority above apps, guests, and AI agents. The release requirements call for Secure Boot to stay on, signed and recoverable boot and updates, limited capabilities for software and devices, and installation that preserves the existing system and data. A missing model or a mistaken AI verdict must never grant permission. Protective changes must not silently lock out the owner or destroy data. These are requirements still being tested on real hardware, not protections proved by the browser simulator.

## AI defending against AI

Peter's guiding idea is to use AI to protect people from hostile AI **and** conventional threats. The planned Guardian watches local security events from networks, peripherals, and agents, then helps explain suspicious behavior in plain language. Examples include a rogue agent, an untrusted USB device, a suspicious download, or a network trick. The defender does not need to out-think a larger attacking model: local context and enforceable boundaries give it a different advantage.

AI can detect, correlate, and advise, but deterministic rules enforce the boundary. Any automatic tightening is limited to predeclared, bounded, reversible, recorded responses. Loosening a safeguard or taking an irreversible action remains the owner's decision. Security events and baselines stay on the machine unless the owner approves a limited summary for sharing.

## Evidence before assurance

PaOS will call a protection ready only after independent adversarial and failure tests, including a missing or wrong model, hostile input, false positives, recovery, and supported real hardware. Releases should state what was tested and what remains unsupported. The beta desktop simulator shows the intended experience; it is not proof of native PaOS security.

## Licensing plan

The final October 2026 project ruling sets **[MPL-2.0](https://www.mozilla.org/en-US/MPL/2.0/) for the PaOS core** (boot, Manager, kernel, PaOS-owned core drivers and hypervisor) and **[Apache-2.0](https://www.apache.org/licenses/LICENSE-2.0) for app interfaces, the SDK, verb definitions and Forge tools**. MPL's file-level copyleft means modified covered core files are shared when distributed. Separate apps, games, drivers, recipes and bundles may use the author's chosen license, including open or proprietary terms. Shipped Linux guests keep their own GPL and other upstream licenses and require the applicable source offer; GPL is **not** the PaOS core license.

Contributions will use DCO sign-off, with no CLA or copyright assignment. The actual source repositories, license files, third-party notices and downloads are coming soon; this introduction and the browser simulator are not a source release.

## Ways to support PaOS

You do not need to write code to help. A simple thank-you matters, and so does a tested code contribution.

**You can help today:**

- **Thanks and word of mouth.** Share the [Forge introduction](https://paosforge.com/) or the [beta simulator](https://gransee.com/review/paos-8bc176296315f468b1089ab1/) with someone who might find the project useful. A public place to leave a note is coming soon.
- **Explore and review the simulator.** Try the planned desktop on a larger screen and note what feels promising, confusing, or missing. It is a design preview, so a simulator observation is not a claim that the native OS already works that way. A public feedback route is coming soon.

**As the public project opens, there will be more ways to help:**

- **Suggest a feature or workflow** and explain the user problem it solves.
- **Write a test report or an honest review.** Clear steps, the exact build and hardware, expected versus observed behavior, and screenshots or logs when safe to share are especially useful.
- **Improve the explanations.** Help with documentation, code comments, a code map, tutorials, translations, and accessibility reviews.
- **Test on your hardware** and contribute reproducible compatibility evidence once verified public builds and test instructions are available.
- **Contribute code.** Fix a bug, improve a widget or tool, build an app or driver, or propose a core change. The planned contribution path uses DCO sign-off, with no CLA or copyright assignment. AI-assisted work is welcome when a human contributor takes responsibility for provenance and testing.
- **Report security problems privately** through the security route that will be published before the public OS beta; please do not post vulnerability details in a public issue.

We are also considering a one-time “buy us lunch” option and optional monthly support for compute costs. **No official donation, Patreon, or bounty link is live yet.** Any such option will appear here only after its terms and destination are ready.

## Coming soon

Public source code, signed downloads, a tested-hardware list, limitations, quick-start instructions, feedback and contribution routes, and security guidance will appear here when the first release candidate is ready. **There is no public OS download or source release yet.**

PaOS Forge™ is a Gransee LLC project directed by Peter Gransee and developed with AI coding agents. The release candidate is being tested on real hardware; each published capability will need its own evidence.
