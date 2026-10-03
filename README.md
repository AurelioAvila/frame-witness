<a href="https://framewitness.pages.dev">
  <img src="assets/frame-witness-cover.jpg" width="1280" alt="Frame Witness Forensics — photo and video examination for Windows. Illustrative laboratory cover; project preview.">
</a>

# Frame Witness

**Photo and video recovery for Windows. Visual review with source context.**

Examine recoverable media on physical SSDs, hard drives and supported disk images.
Move from a file candidate to a visual review, then inspect its source offsets,
SHA-256 hash and available dates without leaving the examination workflow.

**Pre-release** · Windows desktop · Local media analysis · Proprietary software

[Explore the product](https://framewitness.pages.dev/#product) ·
[Examination workflow](#examination-workflow) ·
[Release status](#release-status) ·
[Useful links](#useful-links)

---

## See the media. Keep the context.

Frame Witness is focused on photo and video examination. Its development
workflow combines visual triage with the technical details needed to assess a
finding. A playable frame is an observation; it does not prove that the complete
original survived.

| Examination task | What the workflow provides |
| :--- | :--- |
| **Review candidates visually** | A media gallery, local previews and playback, with sorting by size or available date. |
| **Search surviving content** | Filesystem records and RAW media structures, including supported remnants when current metadata is absent. |
| **Retain source context** | Recorded offsets, SHA-256 hashes and available filesystem information alongside the media. |
| **Read dates with their source** | Filesystem, container and surviving Recycle Bin dates are distinguished; missing dates remain unknown. |
| **Assess recovery quality** | Structural recognition, a decoded frame and complete-file verification remain separate checks. |
| **Keep media local** | Examination runs on the Windows workstation. Scanner and decoder workers use AppContainer isolation. |

<a href="https://framewitness.pages.dev/#examination-title">
  <img src="assets/media-examination.webp" width="1280" alt="Illustrative examiner reviewing landscape video frames at a workstation; this is not an application screenshot or case evidence.">
</a>

*Cover and laboratory scene are AI-generated illustrations. They are not
product screenshots, customer evidence or measured recovery results.*

## Examination workflow

1. **Choose and preserve the source.** Select a supported image or physical disk.
   Prefer an acquired image and a write blocker where appropriate; Windows keeps
   changing a live system disk even when the application only reads it.
2. **Search what remains.** Examine filesystem records and recognizable media
   structures. A metadata filter can exclude items whose metadata did not survive.
3. **Review and verify.** Inspect candidates in the gallery and player, then
   compare their source details, dates and structural findings.
4. **Export with context.** Use a different physical destination for recovered
   media to avoid overwriting potential remnants on the source.

## Useful links

| Destination | What you will find |
| :--- | :--- |
| [Official website](https://framewitness.pages.dev) | Product overview and current availability. |
| [Features and illustrative demo](https://framewitness.pages.dev/#product) | Visual review, source context and local examination. |
| [Workflow and recovery limits](https://framewitness.pages.dev/#workflow) | Source preservation, search, examination and export. |
| [Plans and indicative pricing](https://framewitness.pages.dev/#pricing) | Professional, Lab and Organization licences, with launch prices until 17 October 2026. |
| [Account and licences](https://framewitness.pages.dev/account.html) | Email/password sign-in, credential management, orders, licences and private product support. |
| [Create an account](https://framewitness.pages.dev/#register) | Register or sign in on the homepage; registration is free. |
| [Frequently asked questions](https://framewitness.pages.dev/#questions) | Deleted files, earlier formats, Tor clues, dates and device scope. |
| [Deleted video recovery](https://framewitness.pages.dev/video-recovery) | Surviving records, RAW carving, SSD limits and a reporting checklist. |
| [Tor video traces](https://framewitness.pages.dev/tor-video-traces) | Acquired artifacts and the limits of browser attribution. |
| [Examiner workflow discussion](https://github.com/AurelioAvila/frame-witness/discussions/1) | Share requirements and synthetic examples; no case evidence or sensitive data. |
| [Release channel](https://github.com/AurelioAvila/frame-witness/releases) | Publisher-signed Windows releases with SHA-256 checksums. Scans and previews are free; saving recovered files requires a licence. |
| [Legal information](https://framewitness.pages.dev/legal.html) | Seller information, account data and the [terms of sale and licence](https://framewitness.pages.dev/terms). |

## Release status

**Version 0.32.0 is available as a signed Windows release, with an English interface.**
[Download the signed installer](https://github.com/AurelioAvila/frame-witness/releases/download/v0.32.0/FrameWitness-Setup-0.32.0.exe)
(81.9 MiB) and [read the release notes](https://github.com/AurelioAvila/frame-witness/releases/tag/v0.32.0).
Scans and previews are free. Saving recovered files and the advanced tools require a licence; registration alone does not issue one.

SHA-256: `065324b0c49bb4d165c72169f3a508fc9648f1b71bdde360a0282f8ac28a384e`.
Publisher: Aurelio Avila. Trusted timestamp: Certum.

Local synthetic recovery, preview, playback, isolation and licence checks passed.
A clean Windows installation test was not performed.

Licences are sold from the account area. Launch prices until 17 October 2026 are
€472 for Professional (1 workstation), €1,160.70 for Lab (3) and €1,802.30 for
Organization (5), each a perpetual licence with 12 months of updates. Licences are
delivered immediately and are not refundable; see the
[terms of sale and licence](https://framewitness.pages.dev/terms).

The application source is maintained separately in a private repository.
This public presentation does not grant an open-source licence to the product.
Before operational use, evaluate the eventual release against representative
sources and your organization's requirements.

The release identifies the signed installer and its checksum. Verify
the final artifact before installation. Signing establishes publisher identity
and integrity when verified; it does not guarantee the absence of vulnerabilities
or Windows reputation warnings.

## What recovery can establish

- **Deletion and earlier formats:** recovery depends on accessible surviving
  bytes, fragmentation and supported structures. Overwritten or TRIM-erased
  data cannot be promised.
- **Tor and .onion clues:** available metadata or acquired residues may provide
  leads. An onion reference is not proof that Tor downloaded a video; absent
  artifacts do not rule out browser use.
- **Dates:** recorded timestamps are source values, not proof of recording time
  or a complete deletion history.
- **Isolation:** AppContainer reduces exposure while processing untrusted
  data; it is not an absolute security guarantee.
- **Professional suitability:** no police certification, institutional
  endorsement or superiority over competing tools is claimed.

---

**Focused on:** digital media forensics · photo and video recovery · file carving ·
disk-image examination · Windows storage analysis · visual triage · verification

[Visit Frame Witness](https://framewitness.pages.dev) ·
[Copyright and third-party rights](COPYRIGHT.txt)
