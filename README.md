# spacectl-snap

GitHub Action for building and publishing an **unofficial snap package** of [`spacectl`](https://github.com/spacelift-io/spacectl) to the Snap Store.

**Note:** This snap is **not maintained or endorsed by Spacelift**.  

If you encounter issues, please [open an issue in this repository](https://github.com/dnmmrdr/spacectl-snap/issues) rather than contacting Spacelift.

**Snap Store page:** [https://snapcraft.io/dnmmrdr-spacectl](https://snapcraft.io/dnmmrdr-spacectl)

---

## Installation

You can install the snap directly from the Snap Store:

```
snap install dnmmrdr-spacectl
```
## Usage

### Adding an alias

At present there is no official alias for the snap, therefore a manual alias will need adding to use the standard `spacectl` command, this can be done by running

```
sudo snap alias dnmmrdr-spacectl.spacectl spacectl
```
Note: running this as root is necessary

### Using spacetl

Apart from the exception mentioned expection above, the tool should work in the same way, the documentation for spacectl can be found at the link below

[spacectl documentation](https://docs.spacelift.io/concepts/spacectl)
