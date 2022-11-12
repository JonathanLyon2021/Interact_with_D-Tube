# Interact_with_D-Tube
This is an extra credit exercise in MI4 of Kingsland Universities Blockchain Developer Program

**Exercise: Interact with DTube** (Optional)

# Overview
DTube is the first crypto-decentralized video platform, built on top of the STEEM Blockchain and the IPFS peer-to-
peer network.

According to DTube, the platform aims to become an alternative to YouTube that allows you to watch or upload
videos on IPFS and share or comment about it on the immutable STEEM Blockchain, while earning cryptocurrency
doing it. Because of the decentralized nature of IPFS and the STEEM blockchain, DTube is not able to censor videos,
nor enforce guidelines. Only the users can censor it, through the power of their upvotes and downvotes. On DTube,
there are no hidden algorithms controlling the visibility or monetization of certain videos over others. All of DTube's
data is public and can be analyzed by anyone with an internet connection.
DTube is powered by the Steem Blockchain and IPFS.

It is important to note that DTube is currently on Testnet Mode, therefore, the tokens have no value until the

platform launches on the MainNet, scheduled on 10th of May 2020 *(https://steemit.com/dtube/@dtube/dtube-
mainnet-launch-date-and-adjustments).*

# Goal

• Upload a media to DTube using IPFS and realize that a social media platform for video content is feasible
using decentralized technologies.

# Prerequisites
• A web browser and an internet connection that is able to access *https://d.tube/*
• IPFS Daemon
• A sample video file (No limit)
• A sample thumbnail (Max 2MB)


# 1. Create an account
1. Register an account on *https://signup.d.tube/*

2. Comply with the registration requirements. The first verification step is via email.
Make sure that you use a valid email (not disposable ones) as this is validated by DTube and you won’t be
able to complete the registration process.

3. Linking your Facebook Account is optional, you may skip this step.

4. Next, the platform will generate your cryptographic keys. Note that these keys are generated on the client
side. A different key pair is generated each time you refresh the page.
Save the keys as you’ll need them later.

# 2. Accessing Your Account
1. To login, go to: *https://d.tube/#!/login* and select DTube.

2. Enter your username and private key. Your private key can be found on Step 1.4. If you downloaded the file,
you can also find it there.

3. You are now ready to use the platform.

# 3. Uploading Content
1. To upload a content, to go: *https://d.tube/#!/publish*
There are multiple selections, we’ll add a video by uploading to IPFS.

2. Prepare your IPFS daemon.
In the previous lessons, you have been introduced to IPFS. You should be familiar with it and it should have
been installed in your system.
If you have not, download IPFS according to your operating system here: *https://dist.ipfs.io/#go-ipfs*
Extract it on the same directory with the video file you intend to upload so we can access the binary quickly.

Run the IPFS daemon.

        ipfs daemon

*https://kingslanduniversity.com*

3. Add the file:

        ipfs add FILE_NAME.mp4
      
In this case, the sample video file intended for upload is named demo.mp4
Take note of the hash.

4. Publish the file:

        ipfs name publish IPFS_FILE_HASH

In this case, the sample video’s hash is: *QmTd7oPu7TvgdcHMPysv1kfvFzikvkoefoVXjVzFAY4uXH* **This is just a sample hash, your hash will differ**

5. Once everything is in place, add the hash to the upload video form.

Add the final touches (title, description, tags, etc.). DTube requires you to upload a thumbnail for the video
before publishing it, click on Add Thumbnail to upload one and select your prepared thumbnail.

Click on **Publish Video**.

#### Awesome! You have successfully uploaded a media to DTube.
Due to the decentralized nature of the platform, you may experience uncomfortable loading times when
playing the video compared to other leading platforms (Youtube, Facebook, etc.).





