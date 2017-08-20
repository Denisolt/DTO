# Delivery Time Optimization

The problem of optimizing the delivery time is similar to Multi-armed Bandit problem.
Wiki: In probability theory, the multi-armed bandit problem (sometimes called the K- or N-armed bandit problem) is a problem in which a gambler at a row of slot machines (sometimes known as "one-armed bandits") has to decide which machines to play, how many times to play each machine and in which order to play them. When played, each machine provides a random reward from a probability distribution specific to that machine. The objective of the gambler is to maximize the sum of rewards earned through a sequence of lever pulls.
</br>

### What to look for?
We will be looking for CTR - Click through Ratio. In order to calculate CTR we need to know how many emails were sent within an hour and how many clicks were performed within an hour as well. Example, from 14:00 - 14:59 there were 10 emails sent, 5 emails were clicked. Therefore CTR is 50%.
## The optimum delivery time would be the time with highest CTR.

### Data:
I have provided the dataset I was using with hashed values for the fields with personal information.
__________________
### Execute:
Make sure jupyter and pandas are installed
if they aren't:
```bash
pip install jupyter
pip install pandas
```
then:
```bash
git clone https://github.com/Denisolt/DTO.git
cd DTO-master
jupyter notebook
```
Find the .ipynb file and run it. 
___________

### Credits:
Thanks to [Rajan Khullar](https://github.com/rkhullar) for help and Ravi Kiran Holur Vijay for his article
