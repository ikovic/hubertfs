# hubertfs
![IGruber](https://orig00.deviantart.net/c2c6/f/2010/261/c/1/my_little_tank_by_gorgonbreath-d2yyy0i.jpg)

VFS in a single file implemented in Go

### Why hubertfs
`hubertfs` is a single file VFS. It should be reliable, secure and portable. Kind of like Coloner Gruber's little tank, which was coincidentally named `Hubert`.

### Implementation
Write bytes anywhere in a file: [os.File - ReadAt](https://golang.org/pkg/os/#File.ReadAt)
