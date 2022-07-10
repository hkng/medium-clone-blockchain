
## Deploy to numbai
   npx hardhat clean
   npx hardhat compile
   npx hardhat run scripts/deployMedium.js --network numbai
    Medium deployed to: 0xEBeBE46A50fa0C38E9418e0EAed6DDcf1c0A3455
   npx hardhat verify 0xEBeBE46A50fa0C38E9418e0EAed6DDcf1c0A3455 --network numbai "Medium Blog" "BLOG" "100000000000000000"

## Reference
   https://www.youtube.com/watch?v=8S8unFCq0fM