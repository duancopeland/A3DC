# A3DC

Functional annotation of the A3DC genome, shown as an interactive Krona chart of genomic features and metabolic pathways.

**View the chart:**

- Landing page: https://duancopeland.github.io/A3DC/
- Chart: https://duancopeland.github.io/A3DC/A3DC-genome-Krona.html

GitHub's file viewer shows the chart file as HTML source, so open it through the links above.

## What the chart contains

`A3DC-genome-Krona.html` is a single self-contained HTML file: the Krona viewer and the data are embedded, with no external dependencies.

- Four nested levels, from 23 broad functional categories at the center (for example Protein Metabolism, Carbohydrates, Respiration) to 781 individual functional roles at the edge.
- Each role is counted once, so slice size is the number of distinct roles in that group.
- The search box matches role names, including EC numbers.

## Credits

Chart made with Krona: Ondov, B. D., Bergman, N. H., and Phillippy, A. M. (2011). Interactive metagenomic visualization in a Web browser. *BMC Bioinformatics* 12, 385. https://doi.org/10.1186/1471-2105-12-385

## License

MIT, see [LICENSE](LICENSE). The Krona viewer code embedded in the chart is copyright Battelle National Biodefense Institute and is distributed under its own BSD-style license, reproduced in the header of the HTML file.
