# datadog-tile
Datadog tile for Pivotal Cloud Foundry

Datadog tile to deploy a nozzle to consume metrics from Pivotal Cloud Foundry. The nozzle app is the one defined in this repository (https://github.com/cloudfoundry-incubator/datadog-firehose-nozzle)

The tile definition was built by using the Pivotal Cloud Foundry tile-generator (https://github.com/cf-platform-eng/tile-generator)

You need to install tile-generator to build the product.

## How to Use

```bash
git clone https://github.com/ebornier-pivotal/datadog-tile.git
cd datadog-tile
tile build
```

Then, you can import the datadog-tile-*.pivotal product into Pivotal Cloud Foundry as any product.

![Alt text](nozzle configuration.png?raw=true "Optional Title")

After importing the tile, you just only need one specific configuration for this tile by filling UAA & Loggregator credentials, and Datadog API key. (see https://github.com/cloudfoundry-incubator/datadog-firehose-nozzle to get a good understanding of informations to provide)

Apply changes and play!







