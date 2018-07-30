# graphene\_practice-从入门到实战

任何接触区块链的人都有必要了解石墨烯技术，石墨烯技术将dpos和Lamx融合到一起，具有极强的稳定性和极高的TPS，石墨烯技术可以作为构造企业级区块链的首选技术。

## 石墨烯技术的特点

* dpos共识算法
* 组件化
* 稳定
* 性能好

## 快速导航
* [前言](README.md)
* [整体结构](overview.md)
* [核心流程](core/readme.md)
  * [交易](core/jiao-yi.md)
  * [区块](core/qu-kuai.md)
  * [共识](core/gong-shi.md)
  * [README](core/readme.md)
* [libarary](libarary/readme.md)
  * [README](libarary/readme.md)
  * [app](libarary/app.md)
    * [api](libarary/api.md)
    * [application](libarary/application.md)
    * [database\_api](libarary/databaseapi.md)
    * [api\_access](libarary/apiaccess.md)
    * [full\_account](libarary/fullaccount.md)
    * [impacted](libarary/impacted.md)
    * [plugin](libarary/plugin.md)
  * [chain](libarary/chain.md)
    * [protocol](libarary/chain/protocol.md)
      * [account](libarary/chain/account.md)
      * [address](libarary/chain/address.md)
      * [assert](libarary/chain/assert.md)
      * [asset\_ops](libarary/chain/assetops.md)
      * [authority](libarary/chain/authority.md)
      * [balance](libarary/chain/balance.md)
      * [base](libarary/chain/base.md)
      * [bock](libarary/chain/bock.md)
      * [buyback](libarary/chain/buyback.md)
      * [chain\_parameters](libarary/chain/chainparameters.md)
      * [committee\_member](libarary/chain/committeemember.md)
      * [confidential](libarary/chain/confidential.md)
      * [custom](libarary/chain/custom.md)
      * [config](libarary/chain/config.md)
      * [ext](libarary/chain/ext.md)
      * [fba](libarary/chain/fba.md)
      * [fee\_schedule](libarary/chain/feeschedule.md)
      * [market](libarary/chain/market.md)
      * [memo](libarary/chain/memo.md)
      * [operations](libarary/chain/operations.md)
      * [proposal](libarary/chain/proposal.md)
      * [protocol](libarary/chain/protocol.md)
      * [special\_authority](libarary/chain/specialauthority.md)
      * [transaction](libarary/chain/transaction.md)
      * [transfer](libarary/chain/transfer.md)
      * [types](libarary/chain/types.md)
      * [vesting](libarary/chain/vesting.md)
      * [vote](libarary/chain/vote.md)
      * [withdraw\_permission](libarary/chain/withdrawpermission.md)
      * [witness](libarary/chain/witness.md)
      * [worker](libarary/chain/worker.md)
    * [account\_evaluator](libarary/chain/accountevaluator.md)
    * [account\_object](libarary/chain/accountobject.md)
    * [assert\_evaluator](libarary/chain/assertevaluator.md)
    * [asset\_evaluator](libarary/chain/assetevaluator.md)
    * [asset\_object](libarary/chain/assetobject.md)
    * [balance\_evaluator](libarary/chain/balanceevaluator.md)
    * [balance\_object](libarary/chain/balanceobject.md)
    * [block\_database](libarary/chain/blockdatabase.md)
    * [block\_summary\_object](libarary/chain/blocksummary-object.md)
    * [budget\_record\_object](libarary/chain/budgetrecord-object.md)
    * [buyback](libarary/chain/buyback.md)
    * [buyback\_object](libarary/chain/buybackobject.md)
    * [chain\_property\_object](libarary/chain/chainproperty-object.md)
    * [committee\_member\_evaluator](libarary/chain/committeemember-evaluator.md)
    * [committee\_member\_object](libarary/chain/committeemember-object.md)
    * [confidential\_evaluator](libarary/chain/confidentialevaluator.md)
    * [confidential\_object](libarary/chain/confidentialobject.md)
    * [config](libarary/chain/config.md)
    * [custom\_evaluator](libarary/chain/customevaluator.md)
    * [database](libarary/chain/database.md)
    * [db\_with](libarary/chain/dbwith.md)
    * [evaluator](libarary/chain/evaluator.md)
    * [exceptions](libarary/chain/exceptions.md)
    * [fba\_accumulator\_id](libarary/chain/fbaaccumulator-id.md)
    * [fork\_database](libarary/chain/forkdatabase.md)
    * [genesis\_state](libarary/chain/genesisstate.md)
    * [get\_config](libarary/chain/getconfig.md)
    * [global\_property\_object](libarary/chain/globalproperty-object.md)
    * [immutable\_chain\_parameters](libarary/chain/immutablechain-parameters.md)
    * [internal\_exceptions](libarary/chain/internalexceptions.md)
    * [is\_authorized\_asset](libarary/chain/isauthorized-asset.md)
    * [market\_evaluator](libarary/chain/marketevaluator.md)
    * [market\_object](libarary/chain/marketobject.md)
    * [node\_property\_object](libarary/chain/nodeproperty-object.md)
    * [operation\_history\_object](libarary/chain/operationhistory-object.md)
    * [proposal\_evaluator](libarary/chain/proposalevaluator.md)
    * [proposal\_object](libarary/chain/proposalobject.md)
    * [pts\_address](libarary/chain/ptsaddress.md)
    * [special\_authority](libarary/chain/specialauthority.md)
    * [special\_authority\_object](libarary/chain/specialauthority-object.md)
    * [transaction\_evaluation\_state](libarary/chain/transactionevaluation-state.md)
    * [transaction\_object](libarary/chain/transactionobject.md)
    * [transfer\_evaluator](libarary/chain/transferevaluator.md)
    * [vesting\_balance\_evaluator](libarary/chain/vestingbalance-evaluator.md)
    * [vesting\_balance\_object](libarary/chain/vestingbalance-object.md)
    * [vote\_count](libarary/chain/votecount.md)
    * [withdraw\_permission\_evaluator](libarary/chain/withdrawpermission-evaluator.md)
    * [withdraw\_permission\_object](libarary/chain/withdrawpermission-object.md)
    * [witness\_evaluator](libarary/chain/witnessevaluator.md)
    * [witness\_object](libarary/chain/witnessobject.md)
    * [witness\_schedule\_object](libarary/chain/witnessschedule-object.md)
    * [worker\_evaluator](libarary/chain/workerevaluator.md)
    * [worker\_object](libarary/chain/workerobject.md)
  * [db](libarary/db.md)
    * [flat\_index](libarary/flatindex.md)
    * [fwd](libarary/fwd.md)
    * [generic\_index](libarary/genericindex.md)
    * [index](libarary/index.md)
    * [object](libarary/object.md)
    * [object\_database](libarary/objectdatabase.md)
    * [object\_id](libarary/objectid.md)
    * [simple\_index](libarary/simpleindex.md)
    * [undo\_database](libarary/undodatabase.md)
  * [deterministic\_openssl\_rand](libarary/deterministicopenssl-rand.md)
    * [deterministic\_openssl\_rand](libarary/deterministicopenssl-rand/deterministicopenssl-rand.md)
  * [egenesis](libarary/egenesis.md)
    * [egenesis](libarary/egenesis.md)
  * [fc](libarary/fc.md)
  * [net](libarary/net.md)
    * [config](libarary/config.md)
    * [core\_messages](libarary/coremessages.md)
    * [exceptions](libarary/exceptions.md)
    * [message](libarary/message.md)
    * [message\_oriented\_connection](libarary/messageoriented-connection.md)
    * [node](libarary/node.md)
    * [peer\_connection](libarary/peerconnection.md)
    * [peer\_database](libarary/peerdatabase.md)
    * [stcp\_socket](libarary/stcpsocket.md)
  * [p2p](libarary/p2p.md)
    * [message\_oriented\_connection](libarary/messageoriented-connection.md)
    * [message](libarary/message.md)
    * [node](libarary/node.md)
    * [peer\_connection](libarary/peerconnection.md)
    * [stcp\_socket](libarary/stcpsocket.md)
  * [plugins](libarary/plugins.md)
    * [account\_history](libarary/accounthistory.md)
    * [debug\_witness](libarary/debugwitness.md)
    * [delayed\_node](libarary/delayednode.md)
    * [market\_history](libarary/markethistory.md)
    * [witness](libarary/witness.md)
  * [time](libarary/time.md)
  * [utilities](libarary/utilities.md)
  * [wallet](libarary/wallet.md)
    * [api\_documentation](libarary/apidocumentation.md)
    * [reflect\_util](libarary/reflectutil.md)
    * [wallet](libarary/wallet.md)
* [programs](programs/readme.md)
  * [build\_helpers](programs/buildhelpers.md)
  * [README](programs/readme.md)
  * [cli\_wallet](programs/cliwallet.md)
  * [debug\_node](programs/debugnode.md)
  * [delayed\_node](programs/delayednode.md)
  * [genesis\_util](programs/genesisutil.md)
  * [js\_operation\_serializer](programs/jsoperation-serializer.md)
  * [size\_checker](programs/sizechecker.md)
  * [witness\_node](programs/witnessnode.md)
* [appendix](appendix/readme.md)
  * [附录一：常见问题](appendix/appendix1.md)



## React全栈学习系列
* [Redux学习指南](https://github.com/bitbeen/learn_redux.git)
* [React学习指南](https://github.com/bitbeen/learn_react.git)
* [React-Native学习指南](https://github.com/bitbeen/learn_react_native.git)

## 区块链系列
* [石墨烯技术实战之路](https://github.com/bitbeen/graphene_practice.git)
* [Nxt区块链实战](https://github.com/bitbeen/nxt_practice.git)



