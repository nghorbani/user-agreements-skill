---
title: EULA for software shipped with hardware
description: Draft an end user license agreement for a desktop app and firmware sold with a connected device in the EU and the US, under the Sale of Goods Directive, the Software Directive and the Data Act.
---

# EULA for software shipped with hardware

For a device that ships with a companion app or firmware, sold once, with updates over the air and maybe an optional
cloud plan.

## Example request

```text
We make a Wi-Fi camera sold once to consumers and businesses in Germany, the Netherlands and the US. It ships
with a desktop app under a perpetual licence and gets firmware updates over the air. There is an optional cloud
storage plan billed monthly. The camera sends diagnostic data to us. We need the EULA for the app and the
firmware, the cloud plan terms, a privacy notice and what our packaging and setup flows have to do.
```

## What the skill does

- **Goods with digital elements.** Software that comes with the device and is needed for its functions is part of
  the sale of goods, so the EULA follows the Sale of Goods Directive and § 327a Abs. 3 BGB rather than the rules for
  stand-alone digital content. The duty to supply security and conformity updates is stated as a duty.
- **Software Directive.** The licence keeps the acts the user may always do: back-up copies, observing and testing
  the program, and decompiling for interoperability within the limits of the Directive. An EU buyer's copy is not
  locked against resale where EU law allows it.
- **Product liability.** The Product Liability Directive treats software as a product and keeps the manufacturer
  liable for defects caused by its updates or missing security updates. The skill puts this into the annotations as
  the basis for the warranty and update clauses.
- **Data Act.** A connected product needs pre-contract information about the data it generates: type, format,
  estimated volume, whether it is generated continuously, and how it is stored. These go into the implementation
  register for packaging and setup.
- **Separate tracks.** The one-off device sale and the cloud subscription get their own withdrawal information
  (goods variant and services variant), and business buyers get a track without the consumer rules.
- **Thresholds.** Whether the CCPA applies turns on revenue and on data bought, sold or shared, not on units sold.
  Without those facts it stays undetermined.

## Documents

EULA, cloud plan terms, privacy notice, withdrawal information for each contract type, annotations, open points and
an implementation register for packaging, first-run setup and account flows.

See the full [camera EULA example](../examples/camera-eula/index.md).
