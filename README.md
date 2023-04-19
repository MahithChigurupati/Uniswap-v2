# Uniswap V2 Upgrade

<strong> Milestone: </strong> INFO 7500 - Final Project </br>
<strong> Developer - </strong> SaiMahith Chigurupati </br>
<strong> NUID - </strong> 002700539 </br>
<strong> Email - </strong> chigurupati.sa@northeastern.edu

<strong> Tools used:</strong> Foundry, Solidity

1. UniswapV2 was written three years ago and uses outdated versions of Solidity tools
2. Project goals:
   - Achieve deep knowledge of the UniswapV2 implementation
   - Learn Foundry, the next generation ethereum development environment
3. You may use any online resources for the project.
4. Read through the UniswapV2 code:
   https://github.com/Uniswap/v2-core
   https://github.com/Uniswap/v2-periphery
5. Copy the UniswapV2 code into a new Foundry project
   - The original code had the core and periphery contracts in different repos. We recommend combining them into a single repo to simplify development, and copying libraries rather than using package management.
   - UniswapV2Router01 should not be included.
6. Upgrade the UniswapV2 code to the latest Solidity version that Foundry supports.
7. Write Solidity tests that achieve >95% line coverage for each of the following contracts:
   - UniswapV2Router02
   - UniswapV2Pair
   - UniswapV2Factory
8. Generate and commit a line coverage report to assess the quality of your tests

## Coverage Report:

<img width="846" alt="Uniswap V2 Coverage Report" src="https://user-images.githubusercontent.com/62823527/232962588-58b36dd1-7614-4899-bb64-adee21fca84c.png">
