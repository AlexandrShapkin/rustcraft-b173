# Local asset references

Put the default/vanilla Minecraft Beta 1.7.3 texture pack here for local visual research.

Accepted conventions:

```text
reference/assets/vanilla-b1.7.3/
reference/assets/vanilla-b1.7.3.zip
```

The original Mojang assets are reference-only and intentionally ignored by git. Do not package them
into project releases or bootstrap archives.

For redistributable test/example assets, prefer `reference/external/LibreProg/` after running
`just refs-fetch` and follow that repository's license.
