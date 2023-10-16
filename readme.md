# Renetics App
> renetics stand for "realtime network analitics"

## services / components
- Producer 
  > the producer is responsible for sending network data to message broker  
- Consumer / Processor
  > the consumer / processor is responsible for do the hard work to process and analize data from message broker
- visualizer
  > the visualizer is responsible for displaying the results of data analysis

## tech stack
- golang (producer and consumer)
- red panda (message broker)
- docker & docker-compose (deployment)
- sveltekit (visualizer frontend)
- MongoDB (database)

## data flow
File Data -> Producer -> Message broker -> Consumer -> Visualizer