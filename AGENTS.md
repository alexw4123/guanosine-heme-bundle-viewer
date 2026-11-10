# Original Heme bundle viewer handoff

Read [README.txt](README.txt) for the structural model and its explicit bond records. This repository is the original standalone viewer. The separate [Heme research site](https://github.com/alexw4123/heme) owns the expanded research presentation.

- `index.html` contains the entire viewer and loads NGL from jsDelivr. Its matching source is `guanosine_capped_four_helix_bundle_heme.pdb`.
- From the repo root, run `python -m http.server 8000` and open `http://localhost:8000`. Check atomic and secondary-structure modes. The NGL CDN requires a network connection.
- Preserve the PDB's atom order and explicit `CONECT` records, including the modeled Fe–His coordination links. A structural view is not experimental evidence of binding.
- Route new research-site layout work to the Heme research repository. Treat any change to this viewer or its publication as its own task.
