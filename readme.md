# Libra Ecosystem Proposals (LEPs)

## LEPs Tracks
* **Informational** — A LEP on the `Informational` track is one that is open to adoption by the
  ecosystem, but has not been formally standardized by SDF, and is not endorsed by SDF for
  adoption. Typically a LEP can start as `Informational` to gain traction within the ecosystem
  before moving to the `Standards` track.
* **Standard** — A LEP on the `Standards` track is one that aims for formal standardization and
  endorsement by SDF for adoption. Typically a LEP Standard has a higher bar towards acceptance,
  and it requires approval by 2 SDF members of the LEP Team.

## LEP Status Terms
* **Draft** - A LEP that is currently open for consideration and actively being discussed.
* **Awaiting Decision** — A mature and ready LEP that is ready for approval by the LEP
  Team. If enough the approval requirements are met by LEP team members, the LEP will move towards 
  `FCP`. Otherwise, it'll regress to a `Draft`.
* **FCP** — A LEP that has entered a Final Comment Period (FCP). After one week has passed, during
  which any new concerns should be addressed, the LEP's status will become `Active` or `Final`,
  depending on the content of the LEP.
* **Active** - An actively maintained LEP that is intended for immediate adoption by the entire
  ecosystem by its author(s), and if it is a Standard, by SDF as well. Additional updates may be
  made without changing the LEP number.
* **Final** - A finalized LEP that is intended for immediate adoption by the entire
  ecosystem by its author(s), and if it is a Standard, by SDF as well. A final LEP should only be
  updated to correct errata.

### Additional Statuses
* **Rejected** - A Standards LEP that has been formally rejected by the LEP Team, and will not be
  implemented.
* **Superseded: [New Final LEP]** - A LEP that which was previously final but has been superseded
  by a new, final LEP. Both LEPs should reference each other.

## List of Proposals

| Number | Title | Author | Track | Status |
| --- | --- | --- | --- | --- |

### Draft Proposals

| Number | Title | Author | Track | Status |
| --- | --- | --- | --- | --- |
| [LEP-0010](LEP-0010.md) | libra.toml specification | LibraAPIs | Standard | Draft |
| [LEP-0011](LEP-0011.md) | Federation Protocol | LibraAPIs | Standard | Draft |
| [LEP-0012](LEP-0012.md) | Payment URI Scheme | LibraAPIs | Standard | Draft |

# Contribution Process

This repo is to allow the Libra Ecosystem to enable participants to contribute allowing the Libra network to meet the needs of the ecosystem.

Unlike Core development Proposals (CAPs), Ecosystem Proposals are intended to be a more
dynamic way of introducing standards and protocols utilized in the ecosystem that are built on top
of the Libra Network. It attempts to take a more lightweight process for approval, and much of
its process is inspired by the Stellar Foundation and [IETF][ietf].

Before contributing, consider the following:

- Choose a track to propose your idea on. The bar for accepting an `Informational` LEP is much
  lower than one for a `Standard`, and allows you to promote the LEP independently to gain feedback
  and traction before creating a Standard out of it.
- Gather feedback from discussion on the dev mailing list, chat groups and other forums, and utilize it to begin
  a draft proposal.
- Follow the proposal process listed below. If you're having difficulty moving the proposal
  forward, talk to the buddy that's assigned the LEP; they'll often have guidance on how to move
  things forward, as well as feedback regarding feasibility and how the proposal does or does not
  align with the Stellar Network's goals.

## LEP Process
### Pre-LEP (Initial Discussion)
Introduce your idea on the [slack group](https://libradevs.slack.com) and other community forums dedicated to Libra.

- Make sure to gather feedback and alternative ideas — it's useful before putting together a formal draft!
- Consider contacting experts in a particular area for feedback while you're hashing out the details.

[ietf]: https://ietf.org/
