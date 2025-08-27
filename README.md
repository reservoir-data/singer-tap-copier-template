# Singer Tap Copier Template

To use this [`copier`](https://copier.readthedocs.io) template:

1. Install [`uv`](https://docs.astral.sh/uv/getting-started/installation/)
2. Install `copier`:

   ```bash
   uv tool install copier
   ```

3. Initialize `copier` template directly from Git:

   ```bash
   copier copy --UNSAFE gh:reservoir-data/singer-tap-copier-template path/to/destination
   ```

   Or locally from an already-cloned template repo:

   ```bash
   copier copy --UNSAFE . path/to/destination
   ```

See the [Singer SDK dev guide](https://sdk.meltano.com/en/latest/dev_guide.html).
