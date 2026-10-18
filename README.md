# OpenAI patch additions for StrongPNT

This package reconstructs only the seven full new-file additions under
StrongPNT/Erdos970/ in OpenAI's StrongPNT-lean4341.patch, distributed in
openai/math commit 1581d4cbdd69a0faf34b2089614fe2a814316a6a with its Apache 2.0 license.
Every reconstructed body was compared byte-for-byte with the patch additions
following CRLF-to-LF normalization. No original unpatched StrongPNT files are
included. This is provenance and attribution, not a claim of new authorship
or an independent legal determination concerning third-party material.

The source development credits Math Inc.'s Gauss autoformalization agent with
human supervision for PNT1_ComplexAnalysis, PNT2_LogDerivative,
PNT3_RiemannZeta and PNT4_ZeroFreeRegion. The StrongPNT upstream README
identifies PNT5_Strong, Z0 and ZetaZeroFree as adaptations of the
PrimeNumberTheoremAnd project. These credits are retained. The original
StrongPNT repository itself has no explicit root license; the Apache license
here records OpenAI's licensed patch distribution, not a new license for
that entire upstream repository.

Original StrongPNT build-context pin:
https://github.com/math-inc/strongpnt at 2f5835c322314f55f1026ec2f139d704b7c45c69.
This compatibility package is a candidate until its parent Jacobsthal proof CI passes.
