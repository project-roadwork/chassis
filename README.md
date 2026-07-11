# Chassis?
Project Roadwork's fork of [A-Chassis](https://github.com/lisphm/A-Chassis) as of version 1.7.2. All original credits go to the A-Chassis team. I don't really have a name for this fork yet...

Codeberg (main): https://codeberg.org/project-roadwork/chassis/

GitHub (mirror): https://github.com/project-roadwork/chassis

## Current Changes
* Uses `RunService:BindToSimulation()` except on the `Steering` function when `Tune.PowerSteeringType` is set to `Old`.
   * Modifying BodyGyros is not supported in `BindToSimulation` for some awkward reason
* Uses `--!native`

## License
Like A-Chassis, this fork is licensed under the Mozilla Public License 2.0.
