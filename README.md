# JuliaCh.jl

这里是[Julia.jl](http://svaksha.github.io/Julia.jl)的简体中文版本，这里收集并陈列[Julia语言](https://github.com/JuliaLang)的各种相关资源.

+ [索引](#索引)
+ [证书](#证书)
   + [镜像](#镜像)
+ [贡献你的力量](#贡献你的力量)
   + [参考](#参考)
   + [状态](#状态)
   + [错误报告和PR](#错误报告和PR)

----

# 索引

对于一些基本的程序包，先在github上的[内建程序包管理器](https://github.com/JuliaLang/METADATA.jl)里找一找有没有你要找的，或者查看METADATA中[注册的Julia程序包](http://pkg.julialang.org/)，然后使用内建的包管理器来安装某个版本，当然请不要忘记

For Base packages, check if the package you seek is listed in the [built-in package manager](https://github.com/JuliaLang/METADATA.jl) on github, or check METADATA for [registered Julia packages](http://pkg.julialang.org/), then use the built-in package manager to install it after checking the requirements for respective versions and dont forget the Easter eggs!

To create a package, check out the [Julia Package Development Kit](https://github.com/JuliaLang/PkgDev.jl) and here is a [sample Julia package](https://github.com/JuliaLang/Example.jl) model. The latest interesting package statistics are available at the [Julia Package Ecosystem Pulse](http://pkg.julialang.org/pulse.html) webpage which mirrors the current core development on [github](https://github.com/JuliaLang/julia/pulse). Abandoned packages that no longer have a maintainer or no longer fit into the Julia oraganization that initially hosted the package are listed in the [Julia Archive](https://github.com/JuliaArchive) organisation.


+ [AI.md](https://github.com/svaksha/Julia.jl/blob/master/AI.md) :: Algorithms, DataMining, Data Structures, HMM, ML, NLP, ...
+ [Astronomy.md](https://github.com/svaksha/Julia.jl/blob/master/Astronomy.md) :: Astronomy and Imaging packages.
+ [API.md](https://github.com/svaksha/Julia.jl/blob/master/API.md) :: Language API's - C++, Fortran, Go, Java, JavaScript, MATLAB, Perl, Python, R, ...
+ [Biology.md](https://github.com/svaksha/Julia.jl/blob/master/Biology.md) :: Bioinformatics, genomics, agriculture, food science, medicine, genetic engineering, Neuroscience, et. al...
+ [Build-Automation.md](https://github.com/svaksha/Julia.jl/blob/master/Build-Automation.md) :: Tools for continuous integration (CI),  continuous delivery (CD), Packaging, release engineering (RE), release management (RM), software configuration management (SCM), etc...
+ [Chemistry.md](https://github.com/svaksha/Julia.jl/blob/master/Chemistry.md) :: Analytical chemistry, cheminformatics, crystallography, nanochemistry, nuclear chemistry ...
+ [Community.md](https://github.com/svaksha/Julia.jl/blob/master/Community.md) :: List of community and development links, including events, (un)conferences, forums/ meetup groups, NEWS, etc..
+ [Computer-Graphics.md](https://github.com/svaksha/Julia.jl/blob/master/Computer-Graphics.md) :: Plotting, Graphics and other Visualization tools.
+ [DataBase.md](https://github.com/svaksha/Julia.jl/blob/master/DataBase.md) :: NoSQL, RDBMS and Middleware API's.
+ [Earth-Science.md](https://github.com/svaksha/Julia.jl/blob/master/Earth-Science.md) :: software related to the subcategories of cartography, climatology, geobiology, geochemistry, geography, geoinformatics, geology‎, geophysics‎, geoscience/GIS, geomathematics, meteorology, oceanography, etc...
+ [Hardware.md](https://github.com/svaksha/Julia.jl/blob/master/Hardware.md) :: Software for cross-platform hardware and other API libraries.
+ [HPC.md](https://github.com/svaksha/Julia.jl/blob/master/HPC.md) :: HPC, Distributed Computing, Cloud computing, Cluster computing, Grid computing, Kernels and architectures like ARM, MIPS, GPU, CUDA, etc...
+ [i18n-L10n.md](https://github.com/svaksha/Julia.jl/blob/master/i18n-L10n.md) :: Transliteration, Internationalisation (i18n) and Localisation (L10n)
+ [IO.md](IO.md) :: Input/Output functionality and support for file formats.
+ [Mathematics.md](Mathematics.md):: Algebra, Geometry,... anything Math related.
+ [OpenData.md](https://github.com/svaksha/Julia.jl/blob/master/OpenData.md) :: OpenData, Free Data Sets.
+ [Physics.md](https://github.com/svaksha/Julia.jl/blob/master/Physics.md) :: Julia software related to Physics.
+ [Programming-Paradigms.md](https://github.com/svaksha/Julia.jl/blob/master/Programming-Paradigms.md) :: Programming Paradigms and language concepts that are used in the type system, data types, etc..
+ [Publications.md](https://github.com/svaksha/Julia.jl/blob/master/Publications.md) :: Research Papers (journal and conference publications).
+ [QA.md](https://github.com/svaksha/Julia.jl/blob/master/QA.md) :: Test Driven Development, Sandbox, Functional/ Unit testing,... Quality-related tools.
+ [Resources.md](https://github.com/svaksha/Julia.jl/blob/master/Resources.md) :: blogs, cookbooks, cheatsheets, IJulia NoteBooks, and other non-standard resources.
+ [Statistics.md](https://github.com/svaksha/Julia.jl/blob/master/Statistics.md) :: Actuarial Science, Finance, economics, stochastic, insurance Statistics, Operations research and Benchmarks and Optimization toolkits....
+ [Utilities.md](https://github.com/svaksha/Julia.jl/blob/master/Utilities.md) :: Handy toolkits and other general utilities for your Desktop.
+ [Web-Server.md](https://github.com/svaksha/Julia.jl/blob/master/Web-Server.md) :: HPC, Distributed Computing, Cloud WWW, HTTP, Networking, Servers, etc...


**DISCLAIMER :** As a new language in the scientific computing scene it is frequently in a state of flux due to the addition of new libraries, resulting in frequent changes and page reordering. Since the **Julia.jl** repo only provides a list (of links) of Julia packages out in the wild, it should not be considered an endorsment of any particular package for software quality, technical features, coding style/organization, etc...

----

# 证书
+ COPYRIGHT © 2012-Now [SVAKSHA](http://svaksha.com/pages/Bio), All Rights Reserved.
+ This work is licensed under the Creative Commons Attribution-NonCommercial-ShareAlike 4.0 International License - (CC BY-NC-SA 4.0) as detailed in the [LICENSE.md](https://github.com/svaksha/Julia.jl/blob/master/LICENSE.md) file and ALL references, citations, copies and forks of this work must retain the Copyright, Licence (LICENSE.md file), this permission notice and must [attribute credit](https://en.wikipedia.org/wiki/Creative_Commons_license#Attribution).

## 镜像
+ [Bitbucket](https://bitbucket.org/svaksha/Julia.jl) :: git clone git@bitbucket.org:svaksha/Julia.jl.git
+ [GitLab](https://gitlab.com/svaksha/Julia.jl) :: git clone git@gitlab.com:svaksha/Julia.jl.git
+ [NotABug](https://notabug.org/svaksha/julia.jl) :: git clone git@notabug.org:svaksha/julia.jl.git


# 贡献你的力量
[Contributions](https://github.com/svaksha/Julia.jl/graphs/contributors) to `Julia.jl` are welcome in the form of pull requests (PR). Here are some guidelines and tips on how to submit a Bug Report (BR) and/or [PR](https://github.com/svaksha/Julia.jl/pulls):

## 参考
The Julia community has [ethical guidelines](http://julialang.org/community/standards/) aimed at respecting Copyright, Licenses and attribution standards<sup>{1} and {2}</sup> which you are requested to follow while submitting materials to be listed. Additionally, if you find any material (or code repos) that violates these ethical standards, please file a bug report for their removal from `Julia.jl`.
+ References :
   + {1} https://github.com/JuliaLang/julialang.github.com/issues/200
   + {2} https://github.com/JuliaLang/julialang.github.com/issues/194


## 状态
These [comments](https://github.com/svaksha/Julia.jl/commit/a884fe9e921d57b87d85e970c2f57b8f21025641#commitcomment-15802037) led to a [BR discussing](https://github.com/svaksha/Julia.jl/issues/55) the addition of metadata tags that will enable programmers and package users to easily distinguish the status of various Julia packages that are under various stages of development. Currently, METADATA has a tag system but not all package authors use it, making it harder for lay users to know if the package maintenance is active or not. 

Lets experiment with asking package authors and core-commiters to tag their Julia packages on the following criteria : 

On a scale of 1 to 5 (1=lowest,..5=highest), please rank your package for,

+ `Usability` : Does the package do what it says it does? is it easy to figure out? Is the package production-ready and actively maintained (issues/PRs are responded and resolved in a timely manner, and maintenance and testing is at par with Julia release cycles).
+ `Quality` : Does the package have tests? are there lots of bugs? Do you have good documentation? Can it be used in production environments that expect prompt security patches?
+ `Activity` : Should a 3rd party user bother to use your library, or is it really only intended to be used by the package author? Let's say, an experimental "throw-away toy repo" whose development has now been abandoned.
+ `License` : Which software license do you use? If you dont have a license, please state `None`. 

## 错误报告和PR
1. Add your link as per the top-level Category page within the topic sub-section(s), in _alphabetical order_, with notes (if any) in the markdown files.
2. For broken links or outdated information, submit a bug report (BR), or make the necessary changes and submit a PR. Both are welcome. Please submit separate PR's for each link or change added.
3. For Documentation and cookbooks, check if it matches the categories listed, else, list it on the [Resources.md](https://github.com/svaksha/Julia.jl/blob/master/Resources.md) page.
4. For those unable to use git, create a github account, then fork the `Julia.jl` repo on the user interface. Then edit the page by [clicking on the "pencil" icon on the markdown page](https://help.github.com/articles/editing-files-in-your-repository), then click on save and submit a PR. Github does this [automatically in 8 steps](https://help.github.com/articles/editing-files-in-another-user-s-repository).
