# README for Server Commands 

Welcome! This guide explains the various commands available on the server, grouped into different categories for ease of use. Whether you're teleporting, protecting your area, or managing your account, this guide will help you navigate the commands efficiently.

---

## **Mobility Commands**
These commands help you navigate the world quickly and efficiently.

- **/tpr**: Randomly teleport to a location.
- **/tpa [user]**: Send a teleport request to another player.
- **/tpahere [user]**: Request another player to teleport to you.
- **/tpaccept**: Accept a teleport request.
- **/tpdeny**: Decline a teleport request.
- **/tpcancel**: Cancel a pending teleport request.
- **/spawn**: Teleport back to the spawn point.
- **/sethome [name]**: Set a home point at your current location (up to 4 homes allowed).
- **/delhome [name]**: Delete a set home.
- **/home [name, "bed"]**: Teleport to your set home or bed.
- **/homes**: List all your set homes.
- **/back**: Teleport back to your previous location.
- **/warps**: Show a list of predefined warpable places.
- **/warp [name]**: Warp to a specific location.
- **/kits**: Show available starter kits.
- **/kit [kit_name]**: Claim a specific kit.

---

## **Authentication Commands**
Use these commands to manage your account.

- **/register [password] [confirm_password]**: Register your account.
- **/login [password]**: Log in to your account.

---

## **Regions and Claims (Protect Your Stuff)**
These commands help you protect your area, build safely, and manage your claims.

- **//wand**: Get a stick to select an area (left and right-click to select).
- **//deselect**: Clear the current area selection.
- **//expand [amount] [direction]**: Expand the selected area in a specific direction by a number of blocks.
- **//contract [amount] [direction]**: Contract the selected area by a specific amount of blocks in a certain direction.
- **//expand vert**: Expand the selection vertically from bedrock to skylimit.
- **//chunk**: Select the current chunk, ignoring any previous selection.
- **/rg claim [claim_name]**: Claim a selected area and give it a name (up to 3 claims of 30,000 blocks each).
- **/rg remove [claim_name]**: Remove a claimed area.
- **/rg list**: List all your claimed areas.
- **/rg flags [claim_name]**: Show and modify the properties (flags) of your claim if you're the owner.
- **/rg info [claim_name]**: View and manage ownership and information of your claim.
- **/rg teleport [claim_name]**: Teleport to a set point in your claim (if a teleport point is set).

### **Claiming and Expanding Areas**
1. **Selecting an Area**: 
   Use **//wand** to get a stick and start selecting an area by left-clicking to set the first point and right-clicking to set the second point. You can expand the area using the **//expand** command (e.g., **//expand 20 up** to expand 20 blocks upwards).
   
   More info on area selection can be found here: [WorldEdit Selections](https://worldedit.enginehub.org/en/latest/usage/regions/selections/)

2. **Claiming the Area**: 
   Once you've selected your area, claim it using **/rg claim [claim_name]**. You can manage your claims using commands like **/rg list**, **/rg info**, and **/rg remove**.

### **Claim Flags**
You can modify your claim's properties using **/rg flags [claim_name]** or simply **/rg flags** while inside the claimed area. Some of the things you can control are:

- Chest access (enable/disable)
- Explosions (enable/disable)
- Splash potions (enable/disable)
- Fall damage (enable/disable)
- PvP (enable/disable)
- Entry restrictions (allow/deny)
- Environmental effects (e.g., fire, snow melting, ice melting)
- Teleport points (set and teleport back to a specific point within your claim)

For more details, just navigate the in-chat menu prompted by **/rg flags**.

---

## **Tips**
- If you use a stone axe or better, breaking the bottom block of a tree will make the whole tree fall, saving you time!

---

Feel free to explore and ask if you have any questions regarding these commands. Enjoy your time on the server!
