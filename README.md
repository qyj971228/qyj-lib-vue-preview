```
<Dropdown
  position="top-left"
  :data="[{ name: 'item1' }, { name: 'item2' }]"
  @onSelect="onSelect"
>
  <Button size="l">top-left</Button>
</Dropdown>
```

```
<Menu
  :onSelect="onSelect"
  :data="[
    { name: '1' },
    { name: '2' },
    {
      name: '3',
      children: [
        {
          name: '3-1',
          children: [
            { name: '3-1-1', children: [{ name: '3-1-1-1' }] },
            { name: '3-1-2', children: [{ name: '3-1-2-2' }] },
          ],
        },
        { name: '3-2' },
      ],
    },
    { name: '4' },
    { name: '5' },
  ]"
></Menu>
```