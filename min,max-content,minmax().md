# max-content

    grid-template-columns : max-content 1fr 1fr 1fr

here in this column 1 will take whole width that is required for the content ( text ) present inside that cell 

# min-content

    grid-template-columns : min-content 1fr 1fr 1fr

here in this column 1 will take whole width that is required for the **first word** of the content present inside that cell.


# minmax(_ , _)

    grid-template-columns : ifr 1fr 1fr minmax(150px,300px)

here in this column 4 will take width of 300px _(max)_ if there is **any space left** in the grid if not then at that moment it will start shrinking up-to 150px _(min)_.