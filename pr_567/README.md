Run high_speed_compartor through PnR
This testcase shows the bug exposed in PR #567 (https://github.com/ALIGN-analoglayout/ALIGN-public/pull/567)

```bash
$ALIGN_HOME/PlaceRouteHierFlow/pnr_compiler ./inputs/ high_speed_comparator{.lef,.v,.map} layers.json high_speed_comparator 1 0
```
