### SciUnit and downstream discipline-specific libraries support testing and visualization of test results.  How can interested communities store these tests, optionally schedule new ones, and explore test results across models?  

### We are developing an open-source web application called [**SciDash**](http://dash.scidash.org) to achieve all of these goals. Any SciUnit test result can be deposited there, and models with supported simulation backends can be scheduled for new tests.

<table>
  <tr>
    <td width="100%" align="center"><br><img src="https://github.com/scidash/assets/raw/master/figures/test-scores.png" width="100%"><br>
    A collection of test results across several model types spanning ion channels, circuits, and behavior.</td>
  </tr>
  <tr>
    <td width="100%" align="center"><img src="https://github.com/scidash/assets/raw/master/figures/score_matrix_image.png" width="100%"><br>
    Which olfactory bulb mitral cell model best predicts the selected experimental observations?</td>
  </tr>
</table>

### Visit [**SciDash**](http://dash.scidash.org) for a preview, or interact via REST API using the `scidash-api` package!

### Developer entry-points:
- `pip install scidash-api`
- [API source](http://github.com/metacell/scidash-api)
- [Web front-end source](http://github.com/metacell/scidash)
- [Example simulator backends source](http://github.com/metacell/geppetto-scidash)
