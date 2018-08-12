# How to setup your ThreeFold Farm

Steps:
- [Create an ItsYou.online organization](#iyo-org)
- [Register your farm](#register)
- [Download the EFI (UEFI) bootable image](#download)
- [Format your USB drive](#format)
- [Copy EFI image to USB flash drive](#copy)
- [Boot your node](#boot)

Also see the [Threefold farmers documentation](https://github.com/zero-os/home/blob/master/docs/farmers/README.md#configure-your-nodes).

<a id='iyo-org'></a>

## Create an ItsYou.online organization

Your ThreeFold Farm needs to be associated to an ItsYou.online organization. 

In order to create such an ItsYou.online organization you need an ItsYou.online account. Creating one is simple, head to http://itsyou.online/ and follow the sign-up instructions.

Once logged in to your ItsYou.online account, also creating an ItsYou.online organization is simple.

Click **Organization** from the **Profile** menu in the top right corner:
![](https://raw.githubusercontent.com/zero-os/home/master/docs/farmers/images/iyo-organizations.png)

Now click **+ CREATE NEW**:
![](https://raw.githubusercontent.com/zero-os/home/master/docs/farmers/images/iyo-create-new-org.png)

And finally specify the name of the new ItsYou.online organization and click **CREATE**:
![](https://raw.githubusercontent.com/zero-os/home/master/docs/farmers/images/iyo-create-new-org2.png)

> For the name of the ItsYou.online organization only lower case characters, numbers or spaces are allowed. 

> The name of ItsYou.online organization needs to be globally unique, and therefor also referenced to as the **Global ID** of the ItsYou.online organization.


<a id='register'></a>

## Register your farm

Go to the ThreeFold Grid Capacity web site: https://capacity.threefoldtoken.com

![](images/capacity.png)

In the top right corner click **Register Farm**:

![](images/capacity2.png)

Here you specify:
- **Farm Name**: this can be anything, the name will be displayed next to your node in the listing of the capacity
- **Organization ID**: the global ID of the ItsYou.online organization you created in the previous step
- **TFT Wallet Address**: optionally you can also associate a ThreeFold Token wallet address to your farm
- **Farm Location**: location on the map of your farm

The result of your registration will be a JSON Web Token (JWT), which is your **Farmer ID**. Make sure to copy this token and store it. The **Farmer ID** is required to connect your node to the network.


<a id='boot'></a>

## Boot your node

Boot your node with the USB drive and check the status of your farm on https://capacity.threefoldtoken.com:

![](images/farm.png)

Under **Resource Units** you can click the **details** button which will bring up the details of the selected node:

![](images/farm_details.png)
