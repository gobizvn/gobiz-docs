# Send couriers the dispatch orders
## Purpose
- To send courier the orders and update tracking number on the system

## Guidance
### Solution 1. Send outside M28 system
**Step 1**: Enter "Manage Order", filter as per "For package". Then export that order list and send to couriers (Note: remove no tracking orders)

![danh sách đơn hàng](https://user-images.githubusercontent.com/24457565/134952270-e7047946-e227-42d2-8dbf-fbda6e59ae5a.png)

**Step 2**: Enter "Wait for Pickup", and select "Import tracking number"

![Import mã vận đơn](https://user-images.githubusercontent.com/24457565/134952551-82696048-97ec-461c-aff9-49721a0f6b87.png)

**Step 3**: Download sample file, then fill the data

![Screen Shot 2021-09-27 at 23 57 23](https://user-images.githubusercontent.com/24457565/134952978-7851c74c-af5d-4bbb-9112-076ff582ce4e.png)

**Step 4**: Select warehouse, and upload on the system

### Solution 2. Send through M28 system
**Step 1**: Enter "Wait for Pickup", select "For process". Here is a list of no tracking orders

![Screen Shot 2021-09-28 at 00 00 26](https://user-images.githubusercontent.com/24457565/134953417-fca78004-0f90-409f-a74f-c028edfbcfc8.png)

**Step 2**: Click to mark the orders need to be handled

![Screen Shot 2021-09-28 at 00 02 42](https://user-images.githubusercontent.com/24457565/134953714-9303291e-38d4-4b9a-8eeb-3fd3b0c13b49.png)

**Step 3**: Click on "Create tracking number"

**Step 4**: Re-check 2 tabs as "Error", here shows the orders cannot be sent to couriers
