# Provenance and third-party notices

This file records provenance. It does not grant a license to this archive or to the upstream project.

## Upstream project

- Repository: [matthiasverstraete/3d_recognizer](https://github.com/matthiasverstraete/3d_recognizer)
- Reviewed commit: `b4a02d24826b6f183bd45efce528fd9e5d3aa0d8`
- Primary upstream author visible in Git history: Matthias Verstraete
- Additional upstream contributor visible in Git history: Arnav Kapoor

No project-wide root `LICENSE`, `LICENCE`, `COPYING`, or `NOTICE` file was present at the reviewed upstream commit. This archive does not attempt to relicense upstream source.

## Code retained in this archive

The retained application, camera, dataset, UI, and RandLA-Net files originated in the upstream fork and include a limited set of D455-oriented modifications described in `README.md`. Original authors and contributors retain their respective rights.

## Retained third-party components

The upstream project documented that its retained RandLA-Net implementation was based on [aRI0U/RandLA-Net-pytorch](https://github.com/aRI0U/RandLA-Net-pytorch). No project-wide license was identified in that repository at the time of review, so its presence here must not be interpreted as a general open-source license grant.

The retained implementation also contains narrower third-party components:

- torch-points-kernels-derived utilities accompanied by `randlanet/utils/LICENSE` (MIT);
- `nanoflann.hpp`, which retains its embedded BSD notice;
- KPConv-derived `cloud.h` and `neighbors.h`, accompanied by `randlanet/utils/src/KPCONV_LICENSE` (MIT).

These licenses and notices apply only to their respective components. They do not license the upstream project or this archive as a whole.

## Archived model artifacts

The `models/count`, `models/face`, and `models/signlanguage` checkpoints were produced during the team's D455 experiments and are retained as historical artifacts. Their raw and annotated training data are not distributed. No separate reuse license, safety guarantee, or compatibility guarantee is granted for these checkpoints; see `models/README.md` for hashes and the pickle-deserialization warning.

The upstream pretrained checkpoint, timestamped checkpoints, the body checkpoint, raw and mock data, generated build files, and upstream screenshots are excluded from the current tree. The six screenshots shown in the root README are maintainer-owned documentation images.

## Publication scope

This archive is intended only for publication through the existing GitHub fork. It is not an independently licensed source distribution. Written permission from the relevant copyright holders should be obtained before independent redistribution, Docker image distribution, or commercial use.

## References

- [GitHub Docs: Licensing a repository](https://docs.github.com/en/repositories/managing-your-repositorys-settings-and-features/customizing-your-repository/licensing-a-repository)
- [GitHub Terms of Service: License Grant to Other Users](https://docs.github.com/en/site-policy/github-terms/github-terms-of-service#5-license-grant-to-other-users)
- [Choose a License: No License](https://choosealicense.com/no-permission/)
- [RandLA-Net paper](https://arxiv.org/abs/1911.11236)
- [KPConv source and MIT license](https://github.com/HuguesTHOMAS/KPConv)
