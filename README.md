# Drawbot Cardano
This is the Drawbot on Cardano project

The goal is to run the drawbot on the Cardano blockchain, to give users access to the robots via the blockchain, to record user participation and issue NFTs to participants.

## Setup project on your robot

clone this repo to your robot

```
git clone git@github.com:mischa-robots/drawbot-cardano.git
```

go to the project directory

```
cd drawbot-cardano
```

then build the docker container:

```
docker compose build drawbot
```

and start the container

```
docker compose up
```

or start in background (that will automatically restart the container on robot start)

```
docker compose up -d
```

### License: GNU GENERAL PUBLIC LICENSE V3 (see [LICENSE](LICENSE))

Copyright (C) 2024 Mischa (Michael Schaefer)

This program is free software: you can redistribute it and/or modify
it under the terms of the GNU General Public License as published by
the Free Software Foundation, either version 3 of the License, or
(at your option) any later version.

This program is distributed in the hope that it will be useful,
but WITHOUT ANY WARRANTY; without even the implied warranty of
MERCHANTABILITY or FITNESS FOR A PARTICULAR PURPOSE.  See the
GNU General Public License for more details.

You should have received a copy of the GNU General Public License
along with this program.  If not, see <https://www.gnu.org/licenses/>.