# BorderLayout WebComponent

Traditional Swing BorderLayout like layout as a Polymer 2 WebComponent.

## Example usage

Use slot names NORTH, WEST, CENTER, EAST, and SOUTH to place contetn into layout.

```
    <border-layout>
      <label slot="NORTH">HEADER</label>
      <label slot="WEST">LEFT</label>
      <label slot="CENTER">MAIN</label>
      <label slot="EAST">RIGHT</label>
      <label slot="SOUTH">FOOTER</label>
    </border-layout>
```

## LICENSE

MIT license