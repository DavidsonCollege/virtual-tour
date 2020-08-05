# Davidson College Virtual Tour

## Standard version

The standard version of the tour was created using [Kolor Panotour Pro](https://krpano.com/panotourproupdate/#downloadptp). Updating the 
standard version will require using the Kolor Panotour application to add or edit locations.

The Kolor Panotour application exports the site as a group of HTML files. These are stored in the [standard](https://github.com/DavidsonCollege/virtual-tour/tree/master/standard) directory.

## Accessible Version

The accessible version is generated via the other project files in this repo.

### Locations

Each location in the accessible version is found in the [_locations](https://github.com/DavidsonCollege/virtual-tour/tree/master/_locations) directory.

#### Adding a new location

1. Navigate to the [_locations](https://github.com/DavidsonCollege/virtual-tour/tree/master/_locations) directory
2. Click Add File > Create new file
3. At the top of the page, you will see an input box next to __virtual-tour/_locations/__. Add the location name, all lowercase, using dashes `-` instead of spaces. 
The file extension should be `.md`. For example: `your-new-location.md`
3. Copy the template (below) into the new file
4. replace `<name>` with the name of the location
5. replace `<standard_dir>` with the directory name from the Kolo Panotour export. For example, `pool_11` refers 
to the `[/standard/Indexdata/pool_11](https://github.com/DavidsonCollege/virtual-tour/tree/master/standard/Indexdata/pool_11)` directory, 
this is where the image of the location is found
6. replace `<group>` with one of the following groups:
   - welcome
   - academics
   - the-arts
   - tthletics
   - student-life
 7. replace `<order>` with the order in which you want the location to show up within the group
 8. replace `<description>` with a location description. You can use [Markdown](https://www.markdownguide.org/basic-syntax/) in the 
 description to add headers, links, lists, and other text formatting.
 9. Click the green __Commit New File__ button to add the location

__Location Template__
```
---
name: <name>
image: <standard_dir>
group: <group>
order: <order>
---
<description>
```

#### Editing a location

1. Navigate to the [_locations](https://github.com/DavidsonCollege/virtual-tour/tree/master/_locations) directory
2. Click on the location you want to edit
3. Click on the edit icon (pencil icon on the right-hand side of the screen)
4. Edit the `<name>`, `<standard_dir>`, `<group>`, `<order>`, and `<description>`, see above for additional details
5. Click the green, __Commit Changes__ button


