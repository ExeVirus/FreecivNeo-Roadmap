# FreecivNeo-Roadmap

The following document is the current roadmap for the Freeciv Neo Project

### Current In-order to-do list

1. Create HD Hex Tileset (terrain)
2. Create SDL tool to compile tileset into individual files
3. Collect New Music Score
4. Collect New Sound Set 
5. Test operation of tileset

### Next set of todo list:

1. Create/Pull HD Buildings, Units, and resource icons (0 A.D.)
2. Add new sound files to units and buildings

## Future Roadmap developement

### Ruleset re-definition
 
As of today, February 26, 2020, with Freeciv 3.0, a lot of the ruleset functionality is possible. 
Currently:
1. All base terrain is possible
2. All terrain improvements are possible
3. All wonders are possible
4. All units are possible. 
5. Science based on population is possible by setting tax rates to always 100%, so no science is made from taxes and then using effects (and tile effects) to implement. Effects on science can be percentage based multipliers and individual values too :)
6. Terraforming is 100% possible, and relatively easy for once. 
7. Religion is easily possible at this time. If I were to implement this, it would be fully committed in Lua, and would require creation of new players as religions are adopted and require fake units stationed at every city to keep track of faith contribution and number of citizens that are a given religion. Then, effects would have to be defined for that adoption, and so on. Quite, Quite, Quite difficult to pull off....
8. Culture is much easier at this time, as a system has been developed for it. (we should adopt this for religion and so on). The basic premise is I would define the culture breakpoints for social policies, and when you reach those breakpoints, a "Social Policy" unit is created, that has actions that apply the "extra" to the original** capital tile of a civ (just for ease of tracking). The available acctions are based on present technologies, and extras (policies) already adopted. Help text is going to be messy here. 
9. Specialized Units and Buildings are possible
10. Promotions and National Promotions are possible. Limit is currently 45. so will have to define these later. I see an issue with perhaps special unit flags. Like the Shoeshone and their specialized pathfinder trait that gets carried through the game. 
11. Units are also limited to something like 200. Shouldn't be an issue I think. 
12. Upgrading units is built-in, though I haven't found where one controls that cost....
13. 


### Fighting re-definition

### UI changes

### Tooltips/Popups for events and whatnot




