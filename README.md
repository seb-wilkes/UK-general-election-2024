# Seb's analysis of the UK general election 2024

I took the data as is straight from https://commonslibrary.parliament.uk/research-briefings/cbp-10009/ 

The notebook included so far is to ask the question "How much of a threat was _Reform UK_ to the_ Conservative Party_?". A common message during the latter's campaign was that voting _Reform_ would put _Labour_ in power. I was curious to see how true it was. 

## The main idea

The counterfactual I have done is to ask if a voter of Reform decided to defect, with some probability 'p', what would happen to the election outcome?

For simplicity I am, in effect, taking the expectation of that game. I could do it probabilistically and get an error bar (perhaps a future update?)

After advice from more politically savy individuals, I also added a functionality to say what the probability of switching from Reform to another party.
