# Getting Started with PDF Make

Exploring the PDF make documentation and jump starting with the code. 😇

### Dependencies
```
<script src="https://cdnjs.cloudflare.com/ajax/libs/pdfmake/0.2.7/pdfmake.min.js"></script>
<script src='https://cdnjs.cloudflare.com/ajax/libs/pdfmake/0.2.7/vfs_fonts.min.js'></script>
```

### Create Document Definition
```
const docDefinition = {
    content: [
        'CodeOmelet',
        'Lorem ipsum dolor sit, amet consectetur adipisicing elit. Accusamus, mollitia!'
    ]
};
```

### Open PDF
```
pdfMake.createPdf(docDefinition).open({}, window);
```

### Print PDF
```
pdfMake.createPdf(docDefinition).print();
```

### Download PDF
```
pdfMake.createPdf(docDefinition).download('PDF Make');
```