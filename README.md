# Lets_Play_GANs

The implementation of multi-label conditional generative adversarial network (GAN) on <a href='https://github.com/Maluuba/GeNeVA_datasets/'>i-CLEVR</a> dataset. Our GAN arhitecture doen not include multi-step generation but only include one-step generation.

## Performance

The performance of cGAN is based on our handcrafted testing dataset (test.json and new_test.json).


<table>
	<tr>
		<th>Train set</th>
		<th>Eval set</th>
		<th>Precision</th>
		<th>Recall</th>
		<th>F1-score</th>
	</tr>
	<tr>
		<td>i-CLEVR</td>
		<td>test.json</td>
		<td>83.6</td>
		<td>77.8</td>
		<td>80.6</td>
	</tr>
	<tr>
		<td>i-CLEVR</td>
		<td>new_test.json</td>
		<td>78.6</td>
		<td>85.7</td>
		<td>82.0</td>
    	</tr>
</table>




