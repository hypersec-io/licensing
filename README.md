# HyperI Licensing

**Single Source of Truth** for standard licensing, contribution, and security policy files included in every HyperI GitHub repository.

## Files

| File | Purpose |
|------|---------|
| [`LICENSE`](LICENSE) | FSL-1.1-ALv2 license with Australian law notice |
| [`COMMERCIAL.md`](COMMERCIAL.md) | Commercial licensing requirements and corporate group rules |
| [`CONTRIBUTING.md`](CONTRIBUTING.md) | Contribution guidelines (DCO, Conventional Commits, semantic-release) |
| [`SECURITY.md`](SECURITY.md) | Vulnerability disclosure policy |

## License Summary

HyperI projects are licensed under the **Functional Source License, Version 1.1, ALv2 Future License** (FSL-1.1-ALv2).

- **Permitted**: Internal use, self-hosting, non-commercial education and research
- **Requires commercial licence**: SaaS/PaaS to third parties, OEM embedding, reselling, intra-group hosting
- **Apache 2.0 conversion**: Each version becomes Apache 2.0 on the second anniversary of its release

See [COMMERCIAL.md](COMMERCIAL.md) for full details on when a commercial licence is required.

## Usage

These files are the canonical source for all HyperI repositories. To set up a new repo:

```bash
# Clone and copy to your new repository
git clone https://github.com/hypersec-io/licensing.git /tmp/licensing
cp /tmp/licensing/LICENSE /tmp/licensing/COMMERCIAL.md \
   /tmp/licensing/CONTRIBUTING.md /tmp/licensing/SECURITY.md \
   /path/to/new-repo/
```

## Maintenance

All edits to these files should be made in **this repository only**. Do not modify copies in downstream repositories directly.

## Notes

- The `LICENSE` file references the canonical FSL-1.1-ALv2 at [fsl.software](https://fsl.software)
- Release dates for Apache 2.0 conversion are tracked via GitHub releases in each project
- Copyright year should be updated if creating repos in future years
- All files reference HYPERI PTY LIMITED (ABN 31 622 581 748)

## Contact

- **Commercial licensing**: sales@hyperi.com.au
- **Security reports**: security@hypersec.io
