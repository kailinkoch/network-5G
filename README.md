# The Road to 5G Adoption: A Network Analysis
This was a final project for IT Economics, simulating the diffusion of 5G in the US with graphs. Check out my full report (<a href="https://kailinkoch.github.io/network-5G/INFO%20234%20Final%20Paper.pdf" target="_blank">PDF</a>).


## Abstract
The 5th generational mobile network, otherwise known as 5G, has promised to revolutionize the internet experience with blazing fast speeds. So far, 5G adoption has been slow and halting. In this paper I simulate the impact of speed, product type and network clustering on 5G adoption. I simulate the US mobile market using a network graph, calculate a payoff matrix of 5G and an adoption threshold. I find that current 5G speeds are insufficient to drive network diffusion, though future potential speeds lead to almost a full cascade. 5G home internet and 5G smartphone data demonstrate similar cascades, although 5G home internet has a better payoff given its competitive pricing. Dense clusters in the network without 5G adopters have the potential to block adoption. I end with some recommendations to major carriers based on these findings.

## Research Questions
1. How much does the speed of 5G impact its cascade?
2. Will carriers see greater adoption of 5G smartphone data plans or home internet?
3. Are dense clusters a barrier to adoption of 5G?

## Approach![Screen Shot 2022-05-09 at 7 24 22 AM](https://user-images.githubusercontent.com/68975515/167431262-78f96813-c057-4c8f-a0dc-fd68572b2a4e.png)

To answer these questions, I create network graphs and explore network coordination games. To answer research questions 1 and 2, I created a Barabasi-Albert Graph and evaluated it against a threshold. To answer research question 3, I created a Ring of Cliques graph. I calculated the payoff of switching to 5G data or home internet by comparing the cost per megabyte per second cost of each offering.

### Barabasi-Albert Graph
Assessing whether Node 5 should adopt 5G.
Green = access to 5G, Blue = early adopter starting node.
![Screen Shot 2022-05-09 at 7 20 41 AM](https://user-images.githubusercontent.com/68975515/167430525-c7431f89-27d1-4b47-af64-4a245a6cf65a.png)
![Screen Shot 2022-05-09 at 7 21 02 AM](https://user-images.githubusercontent.com/68975515/167430585-3cc9c241-6ef1-4d17-a1fc-7580d6a405e2.png)

### Ring of Cliques Graph
Assessing whether Node 12 should adopt 5G.
![Screen Shot 2022-05-09 at 7 24 36 AM](https://user-images.githubusercontent.com/68975515/167431307-c7264b34-ba7d-4ba4-8bcd-9527f45da82e.png)
![Screen Shot 2022-05-09 at 7 24 48 AM](https://user-images.githubusercontent.com/68975515/167431349-d66fdc55-ae63-4e60-b5ac-d3a3eec7f47a.png)

## Research Questions, Revisited
1. **How much does the speed of 5G impact its cascade?**
The speed of 5G has a major impact on adoption. Today’s performance, only slightly better than the existing technology, is not enough for 5G to diffuse through a network. Add on the uneven footprint of 5G, and there are even more obstacles to adoption.
2. **Will carriers see greater adoption of 5G smartphone data plans or home internet?**
Both show similar cascade effects. However, 5G home internet’s more competitive payoff could be a major advantage as speeds increase. This is also an entirely new line of business for many of the major carriers, making it an additional revenue stream rather than smartphones which will largely supplant their existing market.
3. **Are dense clusters a barrier to adoption of 5G?**
Yes, clusters are a barrier to 5G adoption. Again, this problem is compounded by the fact that many clusters, particularly rural populations, have no access to 5G at this point.

## Recommendations for Carriers
1. Continue to invest in faster 5G
2. Don’t neglect 5G home internet
3. Prioritize connected early adopters
