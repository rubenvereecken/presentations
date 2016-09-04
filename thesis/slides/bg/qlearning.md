## Q-Learning

<div class="refs">
  Watkins (1989)
</div>

- Learn a policy $\pi(s,a)$
- $q\_\pi (s, a) = \mathbb{E}_\pi[G_t|S_t=s, A_t=a]$
- $Q(S\_t, A\_t) \leftarrow Q(S\_t, A\_t) + \alpha [ R_{t+1} + \gamma max_a Q(S_{t+1}, a) - Q(S_t, A_t) ]$
