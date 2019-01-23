<frontmatter>
  title: "Components"
  footer: footer.md
  siteNav: site-nav.md
</frontmatter>

<include src="./_markbind/common/header.md" />

# Components!
Markbind offers many useful components to make authoring your site even easier

### Panel
<panel header="I'm a panel">
    Does this look familiar?
    <panel header="Another one?">
        Wonder where I saw this before...
        <panel header="One more!">
            Maybe CS2103T?
        </panel>
    </panel>
</panel>

### Popovers
<popover effect="fade" content="Hello!" placement="top"><button class="btn">Hover Over Me</button></popover>

### Boxes
<box type="info">Make your information stand out with boxes</box>
<box type="warning">There are many different boxes to choose from</box>

### Tooltip
Provide contextual <tooltip content="more detail!">information</tooltip>