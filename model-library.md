---
title: 'Genesis'
icon: 'code'
slug: 'model-library'
---

### Genesis is our model library containing general purpose algorithms specifically trained for global financial markets. 

### Our models have been trained to identify directional volatility patterns which remain constant irrespective of market conditions.

<CardGroup cols={1}>
  <Check>In Production</Check>
  <Card
    title="Foundation Model"
    icon="lightbulb" iconType="duotone" color="#8fbc8f"
  >
  <Tabs>
  <Tab title="Description">
    A pre-trained time series model that predicts directional volatility trends.
  </Tab>
  <Tab title="Endpoint">
    https://[BASE_URL]/genesis/foundation-model
  </Tab>
  
  </Tabs>

  </Card>
  <Card
    title="Trading Agent"
    sub
    icon="lightbulb" iconType="duotone" color="#8fbc8f"
  >
  <Tabs>
  <Tab title="Description">
    A ML agent that analyses time series data to generate buy and sell signals. 
  </Tab>
  <Tab title="Endpoint">
    https://[BASE_URL]/genesis/trading-agent
  </Tab>
  </Tabs>
  </Card>
  <Warning>In Development</Warning>
   <Card
    title="TBC"
    icon="lightbulb" iconType="duotone" color="#ffa500"
  >
  <Tabs>
  <Tab title="Description">
    TBC
  </Tab>
  <Tab title="Endpoint">
    TBC
  </Tab>
  </Tabs>
 