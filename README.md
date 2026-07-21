# Model_Information_Supplementary_Material
Supplementary Model Information for RCFAPDYBRB Structures

This repository provides supplementary model information for a study on the selection of ground motion intensity measures for reinforced concrete frames equipped with asynchronized parallel dual-stage yielding buckling-restrained braces (RCFAPDYBRB structures).

## Repository content

The file [Model_Information_Supplementary_Material.pdf](./Model_Information_Supplementary_Material.pdf) contains:

- general information on the frame models, including geometry, concrete grade, member sections, and fundamental periods;
- beam and column reinforcement ratios for 12 frame configurations;
- elevation drawings of the 5-, 7-, 9-, and 11-story frames with inverted-V, V-shaped, and single-diagonal bracing;
- APDYBRB mechanical parameters for the design basis earthquake and maximum considered earthquake parameter sets; and
- conventional buckling-restrained brace parameters used for comparison.

## Model information

The seismic design intensity is 8 (0.2g), and the site characteristic period is 0.35 s. The floor and roof dead and live loads are 6.0 and 2.0 kN/m², respectively.

The analytical cases follow the naming format:

`number of stories-bracing configuration-parameter set-first-stage yield ratio`

For example, `5-IV-D-0.5` denotes a 5-story frame with inverted-V bracing, brace parameters determined for the design basis earthquake level, and a first-stage yield ratio of 0.5.

The first-stage yield ratio is defined as $\alpha=F_{y1}/F_{y2}$.

The abbreviations used in the case IDs are:

- `IV`: inverted-V bracing
- `V`: V-shaped bracing
- `SD`: single-diagonal bracing
- `D`: design basis earthquake parameter set
- `M`: maximum considered earthquake parameter set

For the M parameter set, the second-stage yield force $F_{y2}$ and second-stage activation displacement $\Delta_0$ are twice the corresponding values in the D parameter set, whereas the first- and second-stage initial stiffnesses remain unchanged.

## Citation

If these data are used in research or engineering applications, please cite the associated journal article. The complete citation will be added after publication.

## Questions

Questions about the model information can be submitted through the GitHub Issues page of this repository.
