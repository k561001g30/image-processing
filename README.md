# image-processing
we would like to tear into 50pixs X 50pixs square image,it's definitely have the wast of the picture in the corner.

Forcing to this problem I found that I can split the picture from top-left,top-right,bottom-left and
bottom-right four direction to extend origin pictures.

![image](https://github.com/k561001g30/image-processing/blob/master/gitdescribefig.png)

Pictures are the static data,so,the way tear the 1picture into 4~1pieces(According to the division situation) 

# Zip-directory
```bash
imagetear
    ├── 影像切割
    │   ├── App.config
    │   ├── bin
    │   │   └── Debug
    │   │       ├── ocean_garbage   <--origin pictures
    │   │       │   ├── images (0).jpg
    │   │       │   ├── images (10).jpg
    │   │       │   ├── images (11).jpg
    │   │       │   ├── images (12).jpg
    │   │       │   ├── images (13).jpg
    │   │       │   ├── images (14).jpg
    │   │       │   ├── images (15).jpg
    │   │       │   ├── images (16).jpg
    │   │       │   ├── images (17).jpg
    │   │       │   ├── images (18).jpg
    │   │       │   ├── images (19).jpg
    │   │       │   ├── images (1).jpg
    │   │       │   ├── images (20).jpg
    │   │       │   ├── images (21).jpg
    │   │       │   ├── images (22).jpg
    │   │       │   ├── images (23).jpg
    │   │       │   ├── images (24).jpg
    │   │       │   ├── images (25).jpg
    │   │       │   ├── images (26).jpg
    │   │       │   ├── images (27).jpg
    │   │       │   ├── images (28).jpg
    │   │       │   ├── images (29).jpg
    │   │       │   ├── images (2).jpg
    │   │       │   ├── images (30).jpg
    │   │       │   ├── images (31).jpg
    │   │       │   ├── images (32).jpg
    │   │       │   ├── images (33).jpg
    │   │       │   ├── images (34).jpg
    │   │       │   ├── images (35).jpg
    │   │       │   ├── images (36).jpg
    │   │       │   ├── images (37).jpg
    │   │       │   ├── images (38).jpg
    │   │       │   ├── images (39).jpg
    │   │       │   ├── images (3).jpg
    │   │       │   ├── images (40).jpg
    │   │       │   ├── images (41).jpg
    │   │       │   ├── images (42).jpg
    │   │       │   ├── images (43).jpg
    │   │       │   ├── images (44).jpg
    │   │       │   ├── images (45).jpg
    │   │       │   ├── images (46).jpg
    │   │       │   ├── images (47).jpg
    │   │       │   ├── images (48).jpg
    │   │       │   ├── images (49).jpg
    │   │       │   ├── images (4).jpg
    │   │       │   ├── images (50).jpg
    │   │       │   ├── images (51).jpg
    │   │       │   ├── images (52).jpg
    │   │       │   ├── images (53).jpg
    │   │       │   ├── images (54).jpg
    │   │       │   ├── images (55).jpg
    │   │       │   ├── images (56).jpg
    │   │       │   ├── images (57).jpg
    │   │       │   ├── images (58).jpg
    │   │       │   ├── images (59).jpg
    │   │       │   ├── images (5).jpg
    │   │       │   ├── images (60).jpg
    │   │       │   ├── images (61).jpg
    │   │       │   ├── images (62).jpg
    │   │       │   ├── images (63).jpg
    │   │       │   ├── images (64).jpg
    │   │       │   ├── images (65).jpg
    │   │       │   ├── images (66).jpg
    │   │       │   ├── images (67).jpg
    │   │       │   ├── images (68).jpg
    │   │       │   ├── images (69).jpg
    │   │       │   ├── images (6).jpg
    │   │       │   ├── images (70).jpg
    │   │       │   ├── images (71).jpg
    │   │       │   ├── images (72).jpg
    │   │       │   ├── images (73).jpg
    │   │       │   ├── images (74).jpg
    │   │       │   ├── images (75).jpg
    │   │       │   ├── images (76).jpg
    │   │       │   ├── images (77).jpg
    │   │       │   ├── images (78).jpg
    │   │       │   ├── images (79).jpg
    │   │       │   ├── images (7).jpg
    │   │       │   ├── images (80).jpg
    │   │       │   ├── images (81).jpg
    │   │       │   ├── images (82).jpg
    │   │       │   ├── images (83).jpg
    │   │       │   ├── images (84).jpg
    │   │       │   ├── images (85).jpg
    │   │       │   ├── images (86).jpg
    │   │       │   ├── images (87).jpg
    │   │       │   ├── images (88).jpg
    │   │       │   ├── images (89).jpg
    │   │       │   ├── images (8).jpg
    │   │       │   ├── images (90).jpg
    │   │       │   └── images (9).jpg
    │   │       ├── 影像切割.exe
    │   │       ├── 影像切割.exe.config
    │   │       ├── 影像切割.pdb
    │   │       ├── 影像切割.vshost.exe
    │   │       ├── 影像切割.vshost.exe.config
    │   │       └── 影像切割.vshost.exe.manifest
    │   ├── Form1.cs
    │   ├── Form1.Designer.cs
    │   ├── Form1.resx
    │   ├── obj
    │   │   └── Debug
    │   │       ├── DesignTimeResolveAssemblyReferences.cache
    │   │       ├── DesignTimeResolveAssemblyReferencesInput.cache
    │   │       ├── TemporaryGeneratedFile_036C0B5B-1481-4323-8D20-8F5ADCB23D92.cs
    │   │       ├── TemporaryGeneratedFile_5937a670-0e60-4077-877b-f7221da3dda1.cs
    │   │       ├── TemporaryGeneratedFile_E7A71F73-0F8D-4B9B-B56E-8E70B10BC5D3.cs
    │   │       ├── TempPE
    │   │       │   └── Properties.Resources.Designer.cs.dll
    │   │       ├── 影像切割.csproj.FileListAbsolute.txt
    │   │       ├── 影像切割.csproj.GenerateResource.Cache
    │   │       ├── 影像切割.csprojResolveAssemblyReference.cache
    │   │       ├── 影像切割.exe
    │   │       ├── 影像切割.Form1.resources
    │   │       ├── 影像切割.pdb
    │   │       └── 影像切割.Properties.Resources.resources
    │   ├── Program.cs
    │   ├── Properties
    │   │   ├── AssemblyInfo.cs
    │   │   ├── Resources.Designer.cs
    │   │   ├── Resources.resx
    │   │   ├── Settings.Designer.cs
    │   │   └── Settings.settings
    │   └── 影像切割.csproj
    └── 影像切割.sln
    ```
