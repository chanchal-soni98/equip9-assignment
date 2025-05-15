# equip9-assignment
Problem Statement:
Equip9 allows buyers to place requests for specific equipment, and sellers list their available stock with a price. The goal is to match a buyer’s request with the best-priced seller offering the requested equipment. Implement a system that efficiently finds the seller with the lowest price for each incoming request.
Input:
requests (list of [equipment_type, max_price] requested by buyers)
sellers (list of [equipment_type, price] for available inventory)
Output:
Return a list where each request is matched with the lowest-priced seller (if available). If no seller meets the request criteria, return None for that request.
Example Input:
requests = [("excavator", 50000), ("bulldozer", 70000)]
sellers = [("excavator", 45000), ("bulldozer", 68000), ("excavator", 48000)]

Example Output:
[45000, 68000]  # Matches lowest available prices

var requestsList = [("excavator", 50000), ("bulldozer", 70000)];
var sellers = [("excavator", 45000), ("bulldozer", 68000), ("excavator", 48000)];

var sellerObj = {};

for(let i=0;i<sellers.length;i++){
  
