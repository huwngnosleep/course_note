used to solve Mutual Exclusion problem

- enter()
  - set current state to **Wanted**
  - multicast **request**
  - wait until get **reply** from **all** other processes
  - when get all **reply**, change state to **held**

- on receipt
  - if **state = held** or wanted & if Tj < Ti => add to queue or else **Reply** (use Laport timestamp, which happen first go first)

- exit()
  - change state to **Released** and **Reply** to all **queue**


# maekawa use ricart - agrawala mechanic with states and messages, just optimize in using quorum instead all-to-all messaging