# Tokenomics

### Two Tokens: xCFX and NUT &#x20;

Nucleon has a two token model, which includes xCFX, and NUT.  &#x20;

xCFX is the interest-bearing ERC20 token that represents CFX staked into Nucleon’s PoS pool and it’s interest accrued in CFX over time. There is one type of xCFX, with an uncapped supply determined algorithmically, and will be tradeable. &#x20;

NUT is Nucleon’s governance token, which can be staked to vote and boost staking interest rewards. NUT token allocations are defined by the project team, and will be tradeable on secondary markets. &#x20;

### xCFX Token Model&#x20;

A user mints xCFX by staking CFX into Nucleon’s PoS Pool. xCFX is pegged 1:1 with CFX at network launch, but moving forward, each xCFX will include the basic value of staked CFX plus the interest accrued through Conflux’s PoS mechanism \[insert link to PoS docs].&#x20;

Each xCFX is a claim on the staked CFX plus accrued PoS rewards, where the value of xCFX is determined as follows. After network launch, Nucleon will be accumulating PoS rewards. Suppose user A inputs a CFX (1), and the platform automatically gives user b xCFX according to the ratio of xCFX:CFX, which is c0 (c0 > 1). After the deposit and the time period t, the platform will gain n times of interest reward. Suppose that the interest reward of a single xCFX unit each time is mi (m1, m2, m3 … … mn).. We can assume that the PoS pool continuously gains rewards according to Conflux Network’s PoS mechanism, therefore, mi > 0. As Nucleon accumulates the interest rewards mi, the system will automatically calculate the latest value of each xCFX. From the time when user A deposits a CFX (1) at time t, the value of each xCFX ct is calculated as such: ct = c0 + sum (mi) \[For mi > 0 & ct > c0]. &#x20;

$$
ct = co +
$$

<figure><img src="../.gitbook/assets/image (20).png" alt=""><figcaption></figcaption></figure>

When users withdraw xCFX to CFX, the xCFX to CFX withdraw value is determined the moment the withdrawal operation is confirmed as determined by Conflux POS mechanism - currently: 14 days.&#x20;

&#x20;

### NUT Token Model&#x20;

NUT is Nucleon’s governance token. NUT will be used to vote on proposals deciding the use of protocol treasury funds, and boost staking returns.&#x20;

At launch, Nucleon’s service fee will be set at 10% of the interest earned via CFX staked into Nucleon’s PoS Pool. The service fee will automatically be deducted after each interest acquisition and sent to the protocol’s treasury. &#x20;

Total Supply: 300,000 NUT released over 4 years. &#x20;

<figure><img src="../.gitbook/assets/image (9) (3).png" alt=""><figcaption></figcaption></figure>

The release schedule time chart is as follows:

<figure><img src="../.gitbook/assets/image (4) (2).png" alt=""><figcaption></figcaption></figure>
