English | [简体中文](https://github.com/yunshuipiao/algorithms/blob/master/README_CN.md)

[![Open Source Helpers](https://www.codetriage.com/keon/algorithms/badges/users.svg)](https://www.codetriage.com/keon/algorithms)
[![Build Status](https://travis-ci.org/keon/algorithms.svg?branch=master)](https://travis-ci.org/keon/algorithms)
[![Coverage Status](https://coveralls.io/repos/github/keon/algorithms/badge.svg?branch=master)](https://coveralls.io/github/keon/algorithms?branch=master)

Pythonic Data Structures and Algorithms
=========================================

Minimal and clean example implementations of data structures and algorithms in Python 3.

## Contributing
Thanks for your interest in contributing! There are many ways to contribute to this project. [Get started here](CONTRIBUTING.md)


## Tests

### Use unittest
For running all tests write down:

    $ python3 -m unittest discover tests

For running some specific tests you can do this as following (Ex: sort):

    $ python3 -m unittest tests.test_sort

### Use pytest
For running all tests write down:

    $ python3 -m pytest tests

## Install
If you want to use the API algorithms in your code, it is as simple as:

    $ pip3 install git+https://github.com/keon/algorithms

You can test by creating a python file: (Ex: use `merge_sort` in `sort`)

```python3
from sort import merge_sort

if __name__ == "__main__":
    my_list = [1, 8, 3, 5, 6]
    my_list = merge_sort.merge_sort(my_list)
    print(my_list)
```

## Uninstall
If you want to uninstall algorithms, it is as simple as:

    $ pip3 uninstall -y algorithms

## List of Implementations

- [arrays](arrays)
    - [delete_nth](arrays/delete_nth.py)
    - [flatten](arrays/flatten.py)
    - [garage](arrays/garage.py)
    - [josephus_problem](arrays/josephus_problem.py)
    - [longest_non_repeat](arrays/longest_non_repeat.py/)
    - [merge_intervals](arrays/merge_intervals.py)
    - [missing_ranges](arrays/missing_ranges.py)
    - [plus_one](arrays/plus_one.py)
    - [rotate_array](arrays/rotate_array.py)
    - [summary_ranges](arrays/summary_ranges.py)
    - [three_sum](arrays/three_sum.py)
    - [two_sum](arrays/two_sum.py)
    - [move_zeros_to_end](arrays/move_zeros_to_end.py)
- [backtrack](backtrack)
    - [general_solution.md](backtrack/)
    - [anagram](backtrack/anagram.py)
    - [array_sum_combinations](backtrack/array_sum_combinations.py)
    - [combination_sum](backtrack/combination_sum.py)
    - [expression_add_operators](backtrack/expression_add_operators.py)
    - [factor_combinations](backtrack/factor_combinations.py)
    - [generate_abbreviations](backtrack/generate_abbreviations.py)
    - [generate_parenthesis](backtrack/generate_parenthesis.py)
    - [letter_combination](backtrack/letter_combination.py)
    - [palindrome_partitioning](backtrack/palindrome_partitioning.py)
    - [pattern_match](backtrack/pattern_match.py)
    - [permute](backtrack/permute.py)
    - [permute_unique](backtrack/permute_unique.py)
    - [subsets](backtrack/subsets.py)
    - [subsets_unique](backtrack/subsets_unique.py)
- [bfs](bfs)
    - [shortest_distance_from_all_buildings](bfs/shortest_distance_from_all_buildings.py)
    - [word_ladder](bfs/word_ladder.py)
- [bit](bit)
    - [bytes_int_conversion](bit/bytes_int_conversion.py)
    - [count_ones](bit/count_ones.py)
    - [find_missing_number](bit/find_missing_number.py)
    - [power_of_two](bit/power_of_two.py)
    - [reverse_bits](bit/reverse_bits.py)
    - [single_number](bit/single_number.py)
    - [single_number2](bit/single_number2.py)
    - [single_number3](bit/single_number3.py)
    - [subsets](bit/subsets.py)
    - [add_bitwise_operator](bit/add_bitwise_operator.py)
    - [bit_operation](bit/bit_operation.py)
    - [swap_pair](bit/swap_pair.py)
    - [find_difference](bit/find_difference.py)
    - [has_alternative_bit](bit/has_alternative_bit.py)
    - [insert_bit](bit/insert_bit.py)
    - [remove_bit](bit/remove_bit.py)
- [calculator](calculator)
    - [math_parser](calculator/math_parser.py)
- [dfs](dfs)
    - [all_factors](dfs/all_factors.py)
    - [count_islands](dfs/count_islands.py)
    - [pacific_atlantic](dfs/pacific_atlantic.py)
    - [sudoku_solver](dfs/sudoku_solver.py)
    - [walls_and_gates](dfs/walls_and_gates.py)
- [dp](dp)
    - [buy_sell_stock](dp/buy_sell_stock.py)
    - [climbing_stairs](dp/climbing_stairs.py)
    - [coin_change](dp/coin_change.py)
    - [combination_sum](dp/combination_sum.py)
    - [egg_drop](dp/egg_drop.py)
    - [house_robber](dp/house_robber.py)
    - [job_scheduling](dp/job_scheduling.py)
    - [knapsack](dp/knapsack.py)
    - [longest_increasing](dp/longest_increasing.py)
    - [matrix_chain_order](dp/matrix_chain_order.py)
    - [max_product_subarray](dp/max_product_subarray.py)
    - [max_subarray](dp/max_subarray.py)
    - [min_cost_path](dp/min_cost_path.py)
    - [num_decodings](dp/num_decodings.py)
    - [regex_matching](dp/regex_matching.py)
    - [rod_cut](dp/rod_cut.py)
    - [word_break](dp/word_break.py)
    - [fibonacci](dp/fib.py)
- [graph](graph)
    - [strongly_connected](graph/checkDiGraphStronglyConnected.py)
    - [clone_graph](graph/clone_graph.py)
    - [cycle_detection](graph/cycle_detection.py)
    - [find_all_cliques](graph/find_all_cliques.py)
    - [find_path](graph/find_path.py)
    - [graph](graph/graph.py)
    - [markov_chain](graph/markov_chain.py)
    - [minimum_spanning_tree](graph/minimum_spanning_tree.py)
    - [satisfiability](graph/satisfiability.py)
    - [tarjan](graph/tarjan.py)
    - [traversal](graph/traversal.py)
- [heap](heap)
    - [merge_sorted_k_lists](heap/merge_sorted_k_lists.py)
    - [skyline](heap/skyline.py)
    - [sliding_window_max](heap/sliding_window_max.py)
    - [binary_heap](heap/binary_heap.py)
- [linkedlist](linkedlist)
    - [add_two_numbers](linkedlist/add_two_numbers.py)
    - [copy_random_pointer](linkedlist/copy_random_pointer.py)
    - [delete_node](linkedlist/delete_node.py)
    - [first_cyclic_node](linkedlist/first_cyclic_node.py)
    - [is_cyclic](linkedlist/is_cyclic.py)
    - [is_palindrome](linkedlist/is_palindrome.py)
    - [kth_to_last](linkedlist/kth_to_last.py)
    - [linkedlist](linkedlist/linkedlist.py)
    - [remove_duplicates](linkedlist/remove_duplicates.py)
    - [reverse](linkedlist/reverse.py)
    - [rotate_list](linkedlist/rotate_list.py)
    - [swap_in_pairs](linkedlist/swap_in_pairs.py)
    - [is_sorted](linkedlist/is_sorted.py)
    - [remove_range](linkedlist/remove_range.py)
- [map](map)
    - [hashtable](map/hashtable.py)
    - [separate_chaining_hashtable](map/separate_chaining_hashtable.py)
    - [longest_common_subsequence](map/longest_common_subsequence.py)
    - [randomized_set](map/randomized_set.py)
    - [valid_sudoku](map/valid_sudoku.py)
- [maths](maths)
    - [base_conversion](maths/base_conversion.py)
    - [extended_gcd](maths/extended_gcd.py)
    - [gcd/lcm](maths/gcd.py)
    - [generate_strobogrammtic](maths/generate_strobogrammtic.py)
    - [is_strobogrammatic](maths/is_strobogrammatic.py)
    - [next_bigger](maths/next_bigger.py)
    - [next_perfect_square](maths/next_perfect_square.py)
    - [nth_digit](maths/nth_digit.py)
    - [prime_check](maths/prime_check.py)
    - [primes_sieve_of_eratosthenes](maths/primes_sieve_of_eratosthenes.py)
    - [pythagoras](maths/pythagoras.py)
    - [rabin_miller](maths/rabin_miller.py)
    - [rsa](maths/rsa.py)
    - [sqrt_precision_factor](maths/sqrt_precision_factor.py)
    - [summing_digits](maths/summing_digits.py)
- [matrix](matrix)
    - [sudoku_validator](matrix/sudoku_validator.py)
    - [bomb_enemy](matrix/bomb_enemy.py)
    - [copy_transform](matrix/copy_transform.py)
    - [count_paths](matrix/count_paths.py)
    - [matrix_rotation.txt](matrix/matrix_rotation.txt)
    - [rotate_image](matrix/rotate_image.py)
    - [search_in_sorted_matrix](matrix/search_in_sorted_matrix.py)
    - [sparse_dot_vector](matrix/sparse_dot_vector.py)
    - [sparse_mul](matrix/sparse_mul.py)
    - [spiral_traversal](matrix/spiral_traversal.py)
- [queues](queues)
    - [max_sliding_window](queues/max_sliding_window.py)
    - [moving_average](queues/moving_average.py)
    - [queue](queues/queue.py)
    - [reconstruct_queue](queues/reconstruct_queue.py)
    - [zigzagiterator](queues/zigzagiterator.py)
- [search](search)
    - [binary_search](search/binary_search.py)
    - [first_occurance](search/first_occurance.py)
    - [last_occurance](search/last_occurance.py)
    - [search_insert](search/search_insert.py)
    - [two_sum](search/two_sum.py)
    - [search_range](search/search_range.py)
    - [find_min_rotate](search/find_min_rotate.py)
    - [search_rotate](search/search_rotate.py)
- [set](set)
    - [randomized_set](set/randomized_set.py)
    - [set_covering](set/set_covering.py)
- [sort](sort)
    - [bubble_sort](sort/bubble_sort.py)
    - [comb_sort](sort/comb_sort.py)
    - [counting_sort](sort/counting_sort.py)
    - [heap_sort](sort/heap_sort.py)
    - [insertion_sort](sort/insertion_sort.py)
    - [meeting_rooms](sort/meeting_rooms.py)
    - [merge_sort](sort/merge_sort.py)
    - [quick_sort](sort/quick_sort.py)
    - [selection_sort](sort/selection_sort.py)
    - [sort_colors](sort/sort_colors.py)
    - [topsort](sort/topsort.py)
    - [wiggle_sort](sort/wiggle_sort.py)
- [stack](stack)
    - [longest_abs_path](stack/longest_abs_path.py)
    - [simplify_path](stack/simplify_path.py)
    - [stack](stack/stack.py)
    - [valid_parenthesis](stack/valid_parenthesis.py)
    - [stutter](stack/stutter.py)
    - [switch_pairs](stack/switch_pairs.py)
    - [is_consecutive](stack/is_consecutive.py)
    - [remove_min](stack/remove_min.py)
    - [is_sorted](stack/is_sorted.py)
- [strings](strings)
    - [fizzbuzz](strings/fizzbuzz.py)
    - [delete_reoccurring_characters](strings/delete_reoccurring_characters.py)
    - [strip_url_params](strings/strip_url_params.py)
    - [validate_coordinates](strings/validate_coordinates.py)
    - [domain_extractor](strings/domain_extractor.py)
    - [merge_string_checker](strings/merge_string_checker.py)
    - [add_binary](strings/add_binary.py)
    - [breaking_bad](strings/breaking_bad.py)
    - [decode_string](strings/decode_string.py)
    - [encode_decode](strings/encode_decode.py)
    - [group_anagrams](strings/group_anagrams.py)
    - [int_to_roman](strings/int_to_roman.py)
    - [is_palindrome](strings/is_palindrome.py)
    - [license_number](strings/license_number.py)
    - [make_sentence](strings/make_sentence.py)
    - [multiply_strings](strings/multiply_strings.py)
    - [one_edit_distance](strings/one_edit_distance.py)
    - [rabin_karp](strings/rabin_karp.py)
    - [reverse_string](strings/reverse_string.py)
    - [reverse_vowel](strings/reverse_vowel.py)
    - [reverse_words](strings/reverse_words.py)
    - [roman_to_int](strings/roman_to_int.py)
    - [word_squares](strings/word_squares.py)
- [tree](tree)
    - [bst](tree/tree/bst)
        - [array2bst](tree/bst/array2bst.py)
        - [bst_closest_value](tree/bst/bst_closest_value.py)
        - [BSTIterator](tree/bst/BSTIterator.py)
        - [delete_node](tree/bst/delete_node.py)
        - [is_bst](tree/bst/is_bst.py)
        - [kth_smallest](tree/bst/kth_smallest.py)
        - [lowest_common_ancestor](tree/bst/lowest_common_ancestor.py)
        - [predecessor](tree/bst/predecessor.py)
        - [serialize_deserialize](tree/bst/serialize_deserialize.py)
        - [successor](tree/bst/successor.py)
        - [unique_bst](tree/bst/unique_bst.py)
        - [depth_sum](tree/bst/depth_sum.py)
        - [count_left_node](tree/bst/count_left_node.py)
        - [num_empty](tree/bst/num_empty.py)
        - [height](tree/bst/height.py)
    - [red_black_tree](tree/red_black_tree)
        - [red_black_tree](tree/red_black_tree/red_black_tree.py)
    - [segment_tree](tree/segment_tree)
        - [segment_tree](tree/segment_tree/segment_tree.py)
    - [traversal](tree/traversal)
        - [inorder](tree/traversal/inorder.py)
        - [level_order](tree/traversal/level_order.py)
        - [zigzag](tree/traversal/zigzag.py)
    - [trie](tree/trie)
        - [add_and_search](tree/trie/add_and_search.py)
        - [trie](tree/trie/trie.py)
    - [binary_tree_paths](tree/binary_tree_paths.py)
    - [bintree2list](tree/bintree2list.py)
    - [deepest_left](tree/deepest_left.py)
    - [invert_tree](tree/invert_tree.py)
    - [is_balanced](tree/is_balanced.py)
    - [is_subtree](tree/is_subtree.py)
    - [is_symmetric](tree/is_symmetric.py)
    - [longest_consecutive](tree/longest_consecutive.py)
    - [lowest_common_ancestor](tree/lowest_common_ancestor.py)
    - [max_height](tree/max_height.py)
    - [max_path_sum](tree/max_path_sum.py)
    - [min_height](tree/min_height.py)
    - [path_sum](tree/path_sum.py)
    - [path_sum2](tree/path_sum2.py)
    - [pretty_print](tree/pretty_print.py)
    - [same_tree](tree/same_tree.py)
    - [tree](tree/tree.py)
- [union-find](union-find)
    - [count_islands](union-find/count_islands.py)

## Contributors
The repo is maintained by

* [Keon Kim](https://github.com/keon)
* [Rahul Goswami](https://github.com/goswami-rahul)
* [Christian Bender](https://github.com/christianbender)
* [Ankit Agarwal](https://github.com/ankit167)
* [Hai Hoang Dang](https://github.com/danghai)
* [Saad](https://github.com/SaadBenn)

And thanks to [all the contributors](https://github.com/keon/algorithms/graphs/contributors)
who helped in building the repo.
