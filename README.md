# elixir_interview

Classic sorting algorithms implemented in idiomatic, functional Elixir, one app
per algorithm in an umbrella project, each with its own tests.

| app | algorithm |
|-----|-----------|
| `bubble_sort` | bubble sort |
| `selection_sort` | selection sort |
| `insertion_sort` | insertion sort |
| `comb_sort` | comb sort |
| `merge_sort` | merge sort |
| `quick_sort` | quicksort |
| `heap_sort` | heap sort |
| `counting_sort` | counting sort |
| `radix_sort` | radix sort |
| `main` | runs several algorithms concurrently, one `Task` each, on the same random input |

```sh
mix test            # all apps
cd apps/merge_sort && mix test
```
