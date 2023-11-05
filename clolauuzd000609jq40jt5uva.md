---
title: "Windows Zip is Too Slow! Use This Instead in 2023"
datePublished: Sun Nov 05 2023 09:57:27 GMT+0000 (Coordinated Universal Time)
cuid: clolauuzd000609jq40jt5uva
slug: windows-zip-is-too-slow-use-this-instead-in-2023
cover: https://cdn.hashnode.com/res/hashnode/image/upload/v1699173725092/4d53607f-2d3c-4b11-bd9f-322e326f2ed8.png
tags: speed, foss, files, zip, zipfiles

---

<div data-node-type="callout">
<div data-node-type="callout-emoji">💡</div>
<div data-node-type="callout-text"><strong>Too Long, Didn't Read: </strong>Use <a target="_blank" rel="noopener noreferrer nofollow" href="https://apps.microsoft.com/detail/nanazip/9N8G7TSCL18R" style="pointer-events: none">NanaZip</a>, which is much faster than the Windows inbuilt zip tool. If you want more information and proof, read on below.</div>
</div>

It's been 8 years since the release of Windows 10 and two years since the release of Windows 11.

Over the years, many improvements have occurred to the Windows Operating System, so it'd be easy to assume Windows has the best zip file achieving and reading system.

Unfortunately, as of now, that is not the case. So I sought to write this article to save my readers their precious time with a faster tool.

I'll share the tool, its history, and a comparison of the speeds of the tool compared with the native Windows zip tool.

## Why is the Windows Zip Tool Slow

The interesting question is why the native function for extracting and achieving is so slow.

![](https://cdn.hashnode.com/res/hashnode/image/upload/v1699173150179/787bfb1b-675c-442c-8fed-8c939bb70c81.png align="center")

`Pictures showing the inbuilt zip extraction and compression tools.`

![](https://cdn.hashnode.com/res/hashnode/image/upload/v1699173134632/54b4f185-4970-464d-a931-6b0dee44814f.png align="center")

The main reason is down to the software itself. Perhaps Microsoft has thought that the software functions well enough, so they have not bothered to not improve the inbuilt tool.

Microsoft's thinking may be true for small everyday files, but not for larger files. Larger files still lack in speed in both extracting and archiving compared to faster and more functional third-party tools.

Another probable reason for being relatively slow (though not applicable to every user) is the Windows systems running alongside the zip tool. One major background system is the Windows Defender script, which checks each file before extracting. This can cause a delay in each file check, adding to the extraction time.

## The Zip Tool You Need to Use

The tool in question is [NanaZip](https://apps.microsoft.com/detail/nanazip/9N8G7TSCL18R). It's a FOSS software (completely free and Open-Source) that was a [Microsoft Store App Awards Finalist of 2022](https://blogs.windows.com/windowsdeveloper/2022/05/27/announcing-the-microsoft-store-app-awards-winners/).

NanaZip was [developed by Kenji Mouri](https://github.com/M2Team/NanaZip), or 毛利 研二 in Japanese.

The tool is a fork of the well-known 7-Zip tool . Being based on the same principles, NanaZip has been readied for the modern Windows User.

7-Zip- created in 1999- had been popular due to supporting additional compression formats in addition to the '.zip' format. . 7-Zip also allowed for smaller zip formats, which was more of a concern in its early years due to smaller storage sizes.

NanaZip uses the best of 7-Zip, whilst having a modern look to it as well as on going updates.

Here is a view of the NanaZip interface:

![](https://cdn.hashnode.com/res/hashnode/image/upload/v1699174334321/31687517-b829-43ab-afb1-ca9404dead0c.png align="center")

This is the dual panel view. The view can also be adjusted from the View tab.

The future of NanaZip looks promising, with Kenji actively working on NanaZip, hopefully in the long term future too. The active work includes making a legacy version (NanaZip Classic) that works on 32-Bit and a standard 64-Bit Flagship version.

## NanaZip Vs Native Windows Zip Speed Test

This test was an extraction speed comparison.

For this test I used Windows 11. Both tools were used around the same time.

The size of the file was 5.37 GB whilst compressed. I extracted the same file with both tools. Below are the results.

This was the file size:

![](https://cdn.hashnode.com/res/hashnode/image/upload/v1699175575509/b26d0080-8bbc-4088-9db0-c001e3b7511c.png align="left")

This was the 50 minute time estimated for the windows extraction tool; (I know this was accurate because I had just canceled the same operation halfway):

![](https://cdn.hashnode.com/res/hashnode/image/upload/v1699175588102/7c77f2d4-5372-4863-aa80-f09f04bca0ca.png align="left")

This was the total time for NanaZip, under 5 minutes:

![](https://cdn.hashnode.com/res/hashnode/image/upload/v1699175597102/535f973e-da3c-4761-8c5b-4a7c923d95c6.png align="left")

That's a ten times difference right there!

Another thing to note is the better estimates that NanaZip gives for extraction times.

Of course different environments and files will give different results, but NanaZip will always be quicker than the inbuilt zip extraction tool in my experience.

## Takeaway

* NanaZip is much faster than the inbuilt Windows Zip tool.
    
* Use tools that save your time.
    
* Look for a modern FOSS application
    
* Download NanaZip from the [Microsoft Store](https://apps.microsoft.com/detail/nanazip/9N8G7TSCL18R) or from [GitHub](https://github.com/M2Team/NanaZip).