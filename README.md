# WorkingTitle Modpack

This is a modpack meant to serve as the main modpack for the modded Minecraft servers that will eventually be hosted for the [Coney Poney Discord community.](https://discord.gg/D4z7AHwWqD)
It's designed to be full-featured, but performant, with sane defaults that allow for a pleasant modded Minecraft experience out of the box.

## Testing builds (Requires GitHub Account)

You can find the latest test builds as GitHub Artifacts in the Actions tab, and clicking on the latest workflow run. Then, at the bottom of the page you'll find the .mrpack file to download. GitHub compresses it as a .zip file by default, so be sure to unzip it before trying to import it.

## Building the modpack

Using [Packwiz,](https://github.com/packwiz/packwiz) building the modpack is fairly simple.

In the root directory of this repository, run `packwiz mr export` to export a .mrpack file that you can then import into your launcher of choice.

For more information on how to use Packwiz, visit [their website,](https://packwiz.infra.link/) which has ample documentation on how to use it.
