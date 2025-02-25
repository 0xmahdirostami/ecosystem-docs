---
id: index
title: Index
sidebar_position: 2
---

- [Introduction](./introduction)

## Technical Reference
  - ❱ erc-20
    - ❱ interfaces
      - [Errors](./reference/erc-20/interfaces/Errors)
      - [IERC20Boost](./reference/erc-20/interfaces/IERC20Boost)
      - [IERC20Gauges](./reference/erc-20/interfaces/IERC20Gauges)
      - [IERC20MultiVotes](./reference/erc-20/interfaces/IERC20MultiVotes)
    - [ERC20Boost](./reference/erc-20/ERC20Boost)
    - [ERC20Gauges](./reference/erc-20/ERC20Gauges)
    - [ERC20MultiVotes](./reference/erc-20/ERC20MultiVotes)
  - ❱ erc-4626
    - ❱ interfaces
      - [IERC4626](./reference/erc-4626/interfaces/IERC4626)
      - [IERC4626DepositOnly](./reference/erc-4626/interfaces/IERC4626DepositOnly)
      - [IERC4626MultiToken](./reference/erc-4626/interfaces/IERC4626MultiToken)
      - [IUlyssesERC4626](./reference/erc-4626/interfaces/IUlyssesERC4626)
    - [ERC4626](./reference/erc-4626/ERC4626)
    - [ERC4626DepositOnly](./reference/erc-4626/ERC4626DepositOnly)
    - [ERC4626MultiToken](./reference/erc-4626/ERC4626MultiToken)
    - [UlyssesERC4626](./reference/erc-4626/UlyssesERC4626)
  - ❱ gauges
    - ❱ factories
      - [BaseV2GaugeFactory](./reference/gauges/factories/BaseV2GaugeFactory)
      - [BaseV2GaugeManager](./reference/gauges/factories/BaseV2GaugeManager)
      - [BribesFactory](./reference/gauges/factories/BribesFactory)
      - [UniswapV3GaugeFactory](./reference/gauges/factories/UniswapV3GaugeFactory)
    - ❱ interfaces
      - [IBaseV2Gauge](./reference/gauges/interfaces/IBaseV2Gauge)
      - [IBaseV2GaugeFactory](./reference/gauges/interfaces/IBaseV2GaugeFactory)
      - [IBaseV2GaugeManager](./reference/gauges/interfaces/IBaseV2GaugeManager)
      - [IBribesFactory](./reference/gauges/interfaces/IBribesFactory)
      - [IUniswapV3Gauge](./reference/gauges/interfaces/IUniswapV3Gauge)
      - [IUniswapV3GaugeFactory](./reference/gauges/interfaces/IUniswapV3GaugeFactory)
    - [BaseV2Gauge](./reference/gauges/BaseV2Gauge)
    - [UniswapV3Gauge](./reference/gauges/UniswapV3Gauge)
  - ❱ governance
    - [GovernorBravoConstantsSeverity1](./reference/governance/GovernorBravoConstantsSeverity1)
    - [GovernorBravoConstantsSeverity2](./reference/governance/GovernorBravoConstantsSeverity2)
    - [GovernorBravoConstantsSeverity3](./reference/governance/GovernorBravoConstantsSeverity3)
    - [GovernorBravoConstantsSeverity4](./reference/governance/GovernorBravoConstantsSeverity4)
    - [GovernorBravoConstantsSeverity5](./reference/governance/GovernorBravoConstantsSeverity5)
    - [GovernorBravoConstants](./reference/governance/GovernorBravoConstants)
    - [GovernorBravoDelegate](./reference/governance/GovernorBravoDelegate)
    - [GovernorBravoDelegator](./reference/governance/GovernorBravoDelegator)
    - [GovernorBravoEvents](./reference/governance/GovernorBravoEvents)
    - [GovernorBravoDelegatorStorage](./reference/governance/GovernorBravoDelegatorStorage)
    - [GovernorBravoDelegateStorageV1](./reference/governance/GovernorBravoDelegateStorageV1)
    - [GovernorBravoDelegateStorageV2](./reference/governance/GovernorBravoDelegateStorageV2)
    - [TimelockInterface](./reference/governance/TimelockInterface)
    - [GovTokenInterface](./reference/governance/GovTokenInterface)
    - [GovernorAlpha](./reference/governance/GovernorAlpha)
  - ❱ hermes
    - ❱ interfaces
      - [IBaseV2Minter](./reference/hermes/interfaces/IBaseV2Minter)
      - [IUtilityManager](./reference/hermes/interfaces/IUtilityManager)
      - [IbHermesUnderlying](./reference/hermes/interfaces/IbHermesUnderlying)
    - ❱ minters
      - [BaseV2Minter](./reference/hermes/minters/BaseV2Minter)
    - ❱ tokens
      - [HERMES](./reference/hermes/tokens/HERMES)
      - [bHermesBoost](./reference/hermes/tokens/bHermesBoost)
      - [bHermesGauges](./reference/hermes/tokens/bHermesGauges)
      - [bHermesVotes](./reference/hermes/tokens/bHermesVotes)
    - [UtilityManager](./reference/hermes/UtilityManager)
    - [bHermes](./reference/hermes/bHermes)
  - ❱ maia
    - ❱ factories
      - [PartnerManagerFactory](./reference/maia/factories/PartnerManagerFactory)
    - ❱ interfaces
      - [IBaseVault](./reference/maia/interfaces/IBaseVault)
      - [IERC4626PartnerManager](./reference/maia/interfaces/IERC4626PartnerManager)
      - [IPartnerManagerFactory](./reference/maia/interfaces/IPartnerManagerFactory)
      - [IPartnerUtilityManager](./reference/maia/interfaces/IPartnerUtilityManager)
    - ❱ libraries
      - [DateTimeLib](./reference/maia/libraries/DateTimeLib)
    - ❱ tokens
      - [ERC4626PartnerManager](./reference/maia/tokens/ERC4626PartnerManager)
      - [Maia](./reference/maia/tokens/Maia)
    - [PartnerUtilityManager](./reference/maia/PartnerUtilityManager)
    - [vMaia](./reference/maia/vMaia)
  - ❱ rewards
    - ❱ base
      - [BaseFlywheelRewards](./reference/rewards/base/BaseFlywheelRewards)
      - [FlywheelCore](./reference/rewards/base/FlywheelCore)
    - ❱ booster
      - [FlywheelBoosterGaugeWeight](./reference/rewards/booster/FlywheelBoosterGaugeWeight)
    - ❱ depots
      - [MultiRewardsDepot](./reference/rewards/depots/MultiRewardsDepot)
      - [RewardsDepot](./reference/rewards/depots/RewardsDepot)
      - [SingleRewardsDepot](./reference/rewards/depots/SingleRewardsDepot)
    - ❱ interfaces
      - [IFlywheelAcummulatedRewards](./reference/rewards/interfaces/IFlywheelAcummulatedRewards)
      - [IFlywheelBooster](./reference/rewards/interfaces/IFlywheelBooster)
      - [IFlywheelBribeRewards](./reference/rewards/interfaces/IFlywheelBribeRewards)
      - [IFlywheelCore](./reference/rewards/interfaces/IFlywheelCore)
      - [IRewardsStream](./reference/rewards/interfaces/IRewardsStream)
      - [IFlywheelGaugeRewards](./reference/rewards/interfaces/IFlywheelGaugeRewards)
      - [IFlywheelInstantRewards](./reference/rewards/interfaces/IFlywheelInstantRewards)
      - [IFlywheelRewards](./reference/rewards/interfaces/IFlywheelRewards)
      - [IMultiRewardsDepot](./reference/rewards/interfaces/IMultiRewardsDepot)
      - [IRewardsDepot](./reference/rewards/interfaces/IRewardsDepot)
    - ❱ rewards
      - [FlywheelAcummulatedRewards](./reference/rewards/rewards/FlywheelAcummulatedRewards)
      - [FlywheelBribeRewards](./reference/rewards/rewards/FlywheelBribeRewards)
      - [FlywheelGaugeRewards](./reference/rewards/rewards/FlywheelGaugeRewards)
      - [FlywheelInstantRewards](./reference/rewards/rewards/FlywheelInstantRewards)
    - [FlywheelCoreInstant](./reference/rewards/FlywheelCoreInstant)
    - [FlywheelCore](./reference/rewards/FlywheelCore)
  - ❱ talos
    - ❱ base
      - [TalosBaseStrategy](./reference/talos/base/TalosBaseStrategy)
    - ❱ boost-aggregator
      - [BoostAggregator](./reference/talos/boost-aggregator/BoostAggregator)
    - ❱ factories
      - [BoostAggregatorFactory](./reference/talos/factories/BoostAggregatorFactory)
      - [OptimizerFactory](./reference/talos/factories/OptimizerFactory)
      - [TalosBaseStrategyFactory](./reference/talos/factories/TalosBaseStrategyFactory)
      - [TalosStrategyStakedFactory](./reference/talos/factories/TalosStrategyStakedFactory)
      - [TalosStrategyVanillaFactory](./reference/talos/factories/TalosStrategyVanillaFactory)
    - ❱ interfaces
      - [AutomationCompatibleInterface](./reference/talos/interfaces/AutomationCompatibleInterface)
      - [IBoostAggregator](./reference/talos/interfaces/IBoostAggregator)
      - [IBoostAggregatorFactory](./reference/talos/interfaces/IBoostAggregatorFactory)
      - [IOptimizerFactory](./reference/talos/interfaces/IOptimizerFactory)
      - [ITalosBaseStrategy](./reference/talos/interfaces/ITalosBaseStrategy)
      - [ITalosBaseStrategyFactory](./reference/talos/interfaces/ITalosBaseStrategyFactory)
      - [ITalosManager](./reference/talos/interfaces/ITalosManager)
      - [ITalosOptimizer](./reference/talos/interfaces/ITalosOptimizer)
      - [ITalosStrategyStaked](./reference/talos/interfaces/ITalosStrategyStaked)
      - [ITalosStrategyStakedFactory](./reference/talos/interfaces/ITalosStrategyStakedFactory)
    - ❱ libraries
      - [PoolActions](./reference/talos/libraries/PoolActions)
      - [PoolVariables](./reference/talos/libraries/PoolVariables)
    - ❱ strategies
      - [TalosStrategySimple](./reference/talos/strategies/TalosStrategySimple)
    - [TalosManager](./reference/talos/TalosManager)
    - [TalosOptimizer](./reference/talos/TalosOptimizer)
    - [DeployStaked](./reference/talos/DeployStaked)
    - [TalosStrategyStaked](./reference/talos/TalosStrategyStaked)
    - [DeployVanilla](./reference/talos/DeployVanilla)
    - [TalosStrategyVanilla](./reference/talos/TalosStrategyVanilla)
  - ❱ ulysses-amm
    - ❱ factories
      - [UlyssesPoolDeployer](./reference/ulysses-amm/factories/UlyssesPoolDeployer)
      - [UlyssesFactory](./reference/ulysses-amm/factories/UlyssesFactory)
    - ❱ interfaces
      - [IUlyssesFactory](./reference/ulysses-amm/interfaces/IUlyssesFactory)
      - [IUlyssesPool](./reference/ulysses-amm/interfaces/IUlyssesPool)
      - [IUlyssesRouter](./reference/ulysses-amm/interfaces/IUlyssesRouter)
      - [IUlyssesToken](./reference/ulysses-amm/interfaces/IUlyssesToken)
    - [UlyssesPool](./reference/ulysses-amm/UlyssesPool)
    - [UlyssesRouter](./reference/ulysses-amm/UlyssesRouter)
    - [UlyssesToken](./reference/ulysses-amm/UlyssesToken)
  - ❱ ulysses-omnichain
    - ❱ factories
      - [ArbitrumBranchBridgeAgentFactory](./reference/ulysses-omnichain/factories/ArbitrumBranchBridgeAgentFactory)
      - [BranchBridgeAgentFactory](./reference/ulysses-omnichain/factories/BranchBridgeAgentFactory)
      - [ERC20hTokenBranchFactory](./reference/ulysses-omnichain/factories/ERC20hTokenBranchFactory)
      - [ERC20hTokenRootFactory](./reference/ulysses-omnichain/factories/ERC20hTokenRootFactory)
      - [RootBridgeAgentFactory](./reference/ulysses-omnichain/factories/RootBridgeAgentFactory)
    - ❱ interfaces
      - [IAnycallConfig](./reference/ulysses-omnichain/interfaces/IAnycallConfig)
      - [IAnycallExecutor](./reference/ulysses-omnichain/interfaces/IAnycallExecutor)
      - [IAnycallProxy](./reference/ulysses-omnichain/interfaces/IAnycallProxy)
      - [IApp](./reference/ulysses-omnichain/interfaces/IApp)
      - [IArbitrumBranchPort](./reference/ulysses-omnichain/interfaces/IArbitrumBranchPort)
      - [UserFeeInfo](./reference/ulysses-omnichain/interfaces/UserFeeInfo)
      - [DepositStatus](./reference/ulysses-omnichain/interfaces/DepositStatus)
      - [Deposit](./reference/ulysses-omnichain/interfaces/Deposit)
      - [DepositInput](./reference/ulysses-omnichain/interfaces/DepositInput)
      - [DepositMultipleInput](./reference/ulysses-omnichain/interfaces/DepositMultipleInput)
      - [DepositParams](./reference/ulysses-omnichain/interfaces/DepositParams)
      - [DepositMultipleParams](./reference/ulysses-omnichain/interfaces/DepositMultipleParams)
      - [SettlementParams](./reference/ulysses-omnichain/interfaces/SettlementParams)
      - [SettlementMultipleParams](./reference/ulysses-omnichain/interfaces/SettlementMultipleParams)
      - [IBranchBridgeAgent](./reference/ulysses-omnichain/interfaces/IBranchBridgeAgent)
      - [IBranchBridgeAgentFactory](./reference/ulysses-omnichain/interfaces/IBranchBridgeAgentFactory)
      - [IBranchPort](./reference/ulysses-omnichain/interfaces/IBranchPort)
      - [IBranchRouter](./reference/ulysses-omnichain/interfaces/IBranchRouter)
      - [ICoreBranchRouter](./reference/ulysses-omnichain/interfaces/ICoreBranchRouter)
      - [IERC20hTokenBranch](./reference/ulysses-omnichain/interfaces/IERC20hTokenBranch)
      - [IERC20hTokenBranchFactory](./reference/ulysses-omnichain/interfaces/IERC20hTokenBranchFactory)
      - [IERC20hTokenRoot](./reference/ulysses-omnichain/interfaces/IERC20hTokenRoot)
      - [IERC20hTokenRootFactory](./reference/ulysses-omnichain/interfaces/IERC20hTokenRootFactory)
      - [IMulticall2](./reference/ulysses-omnichain/interfaces/IMulticall2)
      - [IPortStrategy](./reference/ulysses-omnichain/interfaces/IPortStrategy)
      - [SwapCallbackData](./reference/ulysses-omnichain/interfaces/SwapCallbackData)
      - [UserFeeInfo](./reference/ulysses-omnichain/interfaces/UserFeeInfo)
      - [GasPoolInfo](./reference/ulysses-omnichain/interfaces/GasPoolInfo)
      - [SettlementStatus](./reference/ulysses-omnichain/interfaces/SettlementStatus)
      - [Settlement](./reference/ulysses-omnichain/interfaces/Settlement)
      - [SettlementParams](./reference/ulysses-omnichain/interfaces/SettlementParams)
      - [SettlementMultipleParams](./reference/ulysses-omnichain/interfaces/SettlementMultipleParams)
      - [DepositParams](./reference/ulysses-omnichain/interfaces/DepositParams)
      - [DepositMultipleParams](./reference/ulysses-omnichain/interfaces/DepositMultipleParams)
      - [IRootBridgeAgent](./reference/ulysses-omnichain/interfaces/IRootBridgeAgent)
      - [IRootBridgeAgentFactory](./reference/ulysses-omnichain/interfaces/IRootBridgeAgentFactory)
      - [ICoreRootRouter](./reference/ulysses-omnichain/interfaces/ICoreRootRouter)
      - [GasPoolInfo](./reference/ulysses-omnichain/interfaces/GasPoolInfo)
      - [IRootPort](./reference/ulysses-omnichain/interfaces/IRootPort)
      - [IRootRouter](./reference/ulysses-omnichain/interfaces/IRootRouter)
      - [Call](./reference/ulysses-omnichain/interfaces/Call)
      - [IVirtualAccount](./reference/ulysses-omnichain/interfaces/IVirtualAccount)
      - [WETH9](./reference/ulysses-omnichain/interfaces/WETH9)
    - ❱ lib
      - [AnycallFlags](./reference/ulysses-omnichain/lib/AnycallFlags)
    - ❱ token
      - [ERC20hTokenBranch](./reference/ulysses-omnichain/token/ERC20hTokenBranch)
      - [ERC20hTokenRoot](./reference/ulysses-omnichain/token/ERC20hTokenRoot)
    - [DeployArbitrumBranchBridgeAgent](./reference/ulysses-omnichain/DeployArbitrumBranchBridgeAgent)
    - [ArbitrumBranchBridgeAgent](./reference/ulysses-omnichain/ArbitrumBranchBridgeAgent)
    - [ArbitrumBranchPort](./reference/ulysses-omnichain/ArbitrumBranchPort)
    - [ArbitrumCoreBranchRouter](./reference/ulysses-omnichain/ArbitrumCoreBranchRouter)
    - [BaseBranchRouter](./reference/ulysses-omnichain/BaseBranchRouter)
    - [DeployBranchBridgeAgent](./reference/ulysses-omnichain/DeployBranchBridgeAgent)
    - [BranchBridgeAgent](./reference/ulysses-omnichain/BranchBridgeAgent)
    - [DeployBranchBridgeAgentExecutor](./reference/ulysses-omnichain/DeployBranchBridgeAgentExecutor)
    - [BranchBridgeAgentExecutor](./reference/ulysses-omnichain/BranchBridgeAgentExecutor)
    - [BranchPort](./reference/ulysses-omnichain/BranchPort)
    - [CoreBranchRouter](./reference/ulysses-omnichain/CoreBranchRouter)
    - [CoreRootRouter](./reference/ulysses-omnichain/CoreRootRouter)
    - [OutputParams](./reference/ulysses-omnichain/OutputParams)
    - [OutputMultipleParams](./reference/ulysses-omnichain/OutputMultipleParams)
    - [MulticallRootRouter](./reference/ulysses-omnichain/MulticallRootRouter)
    - [CheckParamsLib](./reference/ulysses-omnichain/CheckParamsLib)
    - [DeployRootBridgeAgent](./reference/ulysses-omnichain/DeployRootBridgeAgent)
    - [RootBridgeAgent](./reference/ulysses-omnichain/RootBridgeAgent)
    - [DeployRootBridgeAgentExecutor](./reference/ulysses-omnichain/DeployRootBridgeAgentExecutor)
    - [RootBridgeAgentExecutor](./reference/ulysses-omnichain/RootBridgeAgentExecutor)
    - [RootPort](./reference/ulysses-omnichain/RootPort)
    - [VirtualAccount](./reference/ulysses-omnichain/VirtualAccount)
  - ❱ uni-v3-staker
    - ❱ interfaces
      - [IUniswapV3Staker](./reference/uni-v3-staker/interfaces/IUniswapV3Staker)
    - ❱ libraries
      - [IncentiveId](./reference/uni-v3-staker/libraries/IncentiveId)
      - [IncentiveTime](./reference/uni-v3-staker/libraries/IncentiveTime)
      - [NFTPositionInfo](./reference/uni-v3-staker/libraries/NFTPositionInfo)
      - [RewardMath](./reference/uni-v3-staker/libraries/RewardMath)
    - [UniswapV3Staker](./reference/uni-v3-staker/UniswapV3Staker)
