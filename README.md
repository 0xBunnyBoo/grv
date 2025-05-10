  etherscan: {
    apiKey: {
      // ...
      // Not required. Can be any non-empty string
      gravity: "abc",
    },
    customChains: [
      // ...
      {
        network: "gravity",
        chainId: 1625,
        urls: {
          apiURL: "https://gscan.xyz/api",
          browserURL: "https://gscan.xyz",
          // For Blockscout
          // apiURL: "https://explorer.gravity.xyz/api",
          // browserURL: "https://explorer.gravity.xyz",
        },
      }
    ],
  },
  networks: {
    // ...
    gravity: {
      url: "https://rpc.gravity.xyz",
      chainId: 1625,
      accounts,
    },
  },
