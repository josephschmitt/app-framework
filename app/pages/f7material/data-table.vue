<template>
  <div data-page="data-table" class="page kitchen-sink-material">
    <div class="navbar">
      <div class="navbar-inner">
        <div class="left"><a class="back link icon-only" href="#"><i class="icon icon-back"></i></a></div>
        <div class="center">Data Tables</div>
      </div>
    </div>
    <div class="page-content">
      <div class="content-block-title">Plain table</div>
      <div class="data-table">
        <table>
          <thead>
            <tr>
              <th class="label-cell">Desert (100g serving)</th>
              <th class="numeric-cell">Calories</th>
              <th class="numeric-cell">Fat (g)</th>
              <th class="numeric-cell">Carbs</th>
              <th class="numeric-cell">Protein (g)</th>
            </tr>
          </thead>
          <tbody>
            <tr>
              <td class="label-cell">Frozen yogurt</td>
              <td class="numeric-cell">159</td>
              <td class="numeric-cell">6.0</td>
              <td class="numeric-cell">24</td>
              <td class="numeric-cell">4.0</td>
            </tr>
            <tr>
              <td class="label-cell">Ice cream sandwich</td>
              <td class="numeric-cell">237</td>
              <td class="numeric-cell">9.0</td>
              <td class="numeric-cell">37</td>
              <td class="numeric-cell">4.4</td>
            </tr>
            <tr>
              <td class="label-cell">Eclair</td>
              <td class="numeric-cell">262</td>
              <td class="numeric-cell">16.0</td>
              <td class="numeric-cell">24</td>
              <td class="numeric-cell">6.0</td>
            </tr>
            <tr>
              <td class="label-cell">Cupcake</td>
              <td class="numeric-cell">305</td>
              <td class="numeric-cell">3.7</td>
              <td class="numeric-cell">67</td>
              <td class="numeric-cell">4.3</td>
            </tr>
          </tbody>
        </table>
      </div>
      <div class="content-block-title">Within card</div>
      <div class="card data-table">
        <table>
          <thead>
            <tr>
              <th class="label-cell">Desert (100g serving)</th>
              <th class="numeric-cell">Calories</th>
              <th class="numeric-cell">Fat (g)</th>
              <th class="numeric-cell">Carbs</th>
              <th class="numeric-cell">Protein (g)</th>
            </tr>
          </thead>
          <tbody>
            <tr>
              <td class="label-cell">Frozen yogurt</td>
              <td class="numeric-cell">159</td>
              <td class="numeric-cell">6.0</td>
              <td class="numeric-cell">24</td>
              <td class="numeric-cell">4.0</td>
            </tr>
            <tr>
              <td class="label-cell">Ice cream sandwich</td>
              <td class="numeric-cell">237</td>
              <td class="numeric-cell">9.0</td>
              <td class="numeric-cell">37</td>
              <td class="numeric-cell">4.4</td>
            </tr>
            <tr>
              <td class="label-cell">Eclair</td>
              <td class="numeric-cell">262</td>
              <td class="numeric-cell">16.0</td>
              <td class="numeric-cell">24</td>
              <td class="numeric-cell">6.0</td>
            </tr>
            <tr>
              <td class="label-cell">Cupcake</td>
              <td class="numeric-cell">305</td>
              <td class="numeric-cell">3.7</td>
              <td class="numeric-cell">67</td>
              <td class="numeric-cell">4.3</td>
            </tr>
          </tbody>
        </table>
      </div>
      <div class="content-block-title">Selectable rows</div>
      <div class="data-table data-table-init card">
        <table>
          <thead>
            <tr>
              <th class="checkbox-cell">
                <label class="form-checkbox">
                  <input type="checkbox"><i></i>
                </label>
              </th>
              <th class="label-cell">Desert (100g serving)</th>
              <th class="numeric-cell">Calories</th>
              <th class="numeric-cell">Fat (g)</th>
              <th class="numeric-cell">Carbs</th>
              <th class="numeric-cell">Protein (g)</th>
            </tr>
          </thead>
          <tbody>
            <tr>
              <td class="checkbox-cell">
                <label class="form-checkbox">
                  <input type="checkbox"><i></i>
                </label>
              </td>
              <td class="label-cell">Frozen yogurt</td>
              <td class="numeric-cell">159</td>
              <td class="numeric-cell">6.0</td>
              <td class="numeric-cell">24</td>
              <td class="numeric-cell">4.0</td>
            </tr>
            <tr>
              <td class="checkbox-cell">
                <label class="form-checkbox">
                  <input type="checkbox"><i></i>
                </label>
              </td>
              <td class="label-cell">Ice cream sandwich</td>
              <td class="numeric-cell">237</td>
              <td class="numeric-cell">9.0</td>
              <td class="numeric-cell">37</td>
              <td class="numeric-cell">4.4</td>
            </tr>
            <tr>
              <td class="checkbox-cell">
                <label class="form-checkbox">
                  <input type="checkbox"><i></i>
                </label>
              </td>
              <td class="label-cell">Eclair</td>
              <td class="numeric-cell">262</td>
              <td class="numeric-cell">16.0</td>
              <td class="numeric-cell">24</td>
              <td class="numeric-cell">6.0</td>
            </tr>
            <tr>
              <td class="checkbox-cell">
                <label class="form-checkbox">
                  <input type="checkbox"><i></i>
                </label>
              </td>
              <td class="label-cell">Cupcake</td>
              <td class="numeric-cell">305</td>
              <td class="numeric-cell">3.7</td>
              <td class="numeric-cell">67</td>
              <td class="numeric-cell">4.3</td>
            </tr>
          </tbody>
        </table>
      </div>
      <div class="content-block-title">Tablet-only columns</div>
      <div class="content-block">
        <p>"Comments" column will be visible only on large screen devices (tablets)</p>
      </div>
      <div class="data-table data-table-init card">
        <table>
          <thead>
            <tr>
              <th class="checkbox-cell">
                <label class="form-checkbox">
                  <input type="checkbox"><i></i>
                </label>
              </th>
              <th class="label-cell">Desert (100g serving)</th>
              <th class="numeric-cell">Calories</th>
              <th class="numeric-cell">Fat (g)</th>
              <th class="numeric-cell">Carbs</th>
              <th class="numeric-cell">Protein (g)</th>
              <th class="tablet-only"><i class="material-icons">message</i> Comments</th>
            </tr>
          </thead>
          <tbody>
            <tr>
              <td class="checkbox-cell">
                <label class="form-checkbox">
                  <input type="checkbox"><i></i>
                </label>
              </td>
              <td class="label-cell">Frozen yogurt</td>
              <td class="numeric-cell">159</td>
              <td class="numeric-cell">6.0</td>
              <td class="numeric-cell">24</td>
              <td class="numeric-cell">4.0</td>
              <td class="tablet-only">I like frozen yogurt</td>
            </tr>
            <tr>
              <td class="checkbox-cell">
                <label class="form-checkbox">
                  <input type="checkbox"><i></i>
                </label>
              </td>
              <td class="label-cell">Ice cream sandwich</td>
              <td class="numeric-cell">237</td>
              <td class="numeric-cell">9.0</td>
              <td class="numeric-cell">37</td>
              <td class="numeric-cell">4.4</td>
              <td class="tablet-only">But like ice cream more</td>
            </tr>
            <tr>
              <td class="checkbox-cell">
                <label class="form-checkbox">
                  <input type="checkbox"><i></i>
                </label>
              </td>
              <td class="label-cell">Eclair</td>
              <td class="numeric-cell">262</td>
              <td class="numeric-cell">16.0</td>
              <td class="numeric-cell">24</td>
              <td class="numeric-cell">6.0</td>
              <td class="tablet-only">Super tasty</td>
            </tr>
            <tr>
              <td class="checkbox-cell">
                <label class="form-checkbox">
                  <input type="checkbox"><i></i>
                </label>
              </td>
              <td class="label-cell">Cupcake</td>
              <td class="numeric-cell">305</td>
              <td class="numeric-cell">3.7</td>
              <td class="numeric-cell">67</td>
              <td class="numeric-cell">4.3</td>
              <td class="tablet-only">Don't like it</td>
            </tr>
          </tbody>
        </table>
      </div>
      <div class="content-block-title">Within card with title and actions</div>
      <div class="data-table data-table-init card">
        <div class="card-header">
          <div class="data-table-title">Nutrition</div>
          <div class="data-table-actions"><a class="link icon-only"><i class="icon material-icons">sort</i></a><a class="link icon-only"><i class="icon material-icons">more_vert</i></a></div>
        </div>
        <div class="card-content">
          <table>
            <thead>
              <tr>
                <th class="checkbox-cell">
                  <label class="form-checkbox">
                    <input type="checkbox"><i></i>
                  </label>
                </th>
                <th class="label-cell">Desert (100g serving)</th>
                <th class="numeric-cell">Calories</th>
                <th class="numeric-cell">Fat (g)</th>
                <th class="numeric-cell">Carbs</th>
                <th class="numeric-cell">Protein (g)</th>
                <th class="tablet-only"><i class="material-icons">message</i> Comments</th>
              </tr>
            </thead>
            <tbody>
              <tr>
                <td class="checkbox-cell">
                  <label class="form-checkbox">
                    <input type="checkbox"><i></i>
                  </label>
                </td>
                <td class="label-cell">Frozen yogurt</td>
                <td class="numeric-cell">159</td>
                <td class="numeric-cell">6.0</td>
                <td class="numeric-cell">24</td>
                <td class="numeric-cell">4.0</td>
                <td class="tablet-only">I like frozen yogurt</td>
              </tr>
              <tr>
                <td class="checkbox-cell">
                  <label class="form-checkbox">
                    <input type="checkbox"><i></i>
                  </label>
                </td>
                <td class="label-cell">Ice cream sandwich</td>
                <td class="numeric-cell">237</td>
                <td class="numeric-cell">9.0</td>
                <td class="numeric-cell">37</td>
                <td class="numeric-cell">4.4</td>
                <td class="tablet-only">But like ice cream more</td>
              </tr>
              <tr>
                <td class="checkbox-cell">
                  <label class="form-checkbox">
                    <input type="checkbox"><i></i>
                  </label>
                </td>
                <td class="label-cell">Eclair</td>
                <td class="numeric-cell">262</td>
                <td class="numeric-cell">16.0</td>
                <td class="numeric-cell">24</td>
                <td class="numeric-cell">6.0</td>
                <td class="tablet-only">Super tasty</td>
              </tr>
              <tr>
                <td class="checkbox-cell">
                  <label class="form-checkbox">
                    <input type="checkbox"><i></i>
                  </label>
                </td>
                <td class="label-cell">Cupcake</td>
                <td class="numeric-cell">305</td>
                <td class="numeric-cell">3.7</td>
                <td class="numeric-cell">67</td>
                <td class="numeric-cell">4.3</td>
                <td class="tablet-only">Don't like it</td>
              </tr>
            </tbody>
          </table>
        </div>
      </div>
      <div class="content-block-title">Sortable columns</div>
      <div class="data-table data-table-init card">
        <div class="card-header">
          <div class="data-table-title">Nutrition</div>
          <div class="data-table-actions"><a class="link icon-only"><i class="icon material-icons">sort</i></a><a class="link icon-only"><i class="icon material-icons">more_vert</i></a></div>
        </div>
        <div class="card-content">
          <table>
            <thead>
              <tr>
                <th class="checkbox-cell">
                  <label class="form-checkbox">
                    <input type="checkbox"><i></i>
                  </label>
                </th>
                <th class="label-cell sortable-cell sortable-active">Desert (100g serving)</th>
                <th class="numeric-cell sortable-cell">Calories</th>
                <th class="numeric-cell sortable-cell">Fat (g)</th>
                <th class="numeric-cell sortable-cell">Carbs</th>
                <th class="numeric-cell sortable-cell">Protein (g)</th>
                <th class="tablet-only"><i class="material-icons">message</i> Comments</th>
              </tr>
            </thead>
            <tbody>
              <tr>
                <td class="checkbox-cell">
                  <label class="form-checkbox">
                    <input type="checkbox"><i></i>
                  </label>
                </td>
                <td class="label-cell">Frozen yogurt</td>
                <td class="numeric-cell">159</td>
                <td class="numeric-cell">6.0</td>
                <td class="numeric-cell">24</td>
                <td class="numeric-cell">4.0</td>
                <td class="tablet-only">I like frozen yogurt</td>
              </tr>
              <tr>
                <td class="checkbox-cell">
                  <label class="form-checkbox">
                    <input type="checkbox"><i></i>
                  </label>
                </td>
                <td class="label-cell">Ice cream sandwich</td>
                <td class="numeric-cell">237</td>
                <td class="numeric-cell">9.0</td>
                <td class="numeric-cell">37</td>
                <td class="numeric-cell">4.4</td>
                <td class="tablet-only">But like ice cream more</td>
              </tr>
              <tr>
                <td class="checkbox-cell">
                  <label class="form-checkbox">
                    <input type="checkbox"><i></i>
                  </label>
                </td>
                <td class="label-cell">Eclair</td>
                <td class="numeric-cell">262</td>
                <td class="numeric-cell">16.0</td>
                <td class="numeric-cell">24</td>
                <td class="numeric-cell">6.0</td>
                <td class="tablet-only">Super tasty</td>
              </tr>
              <tr>
                <td class="checkbox-cell">
                  <label class="form-checkbox">
                    <input type="checkbox"><i></i>
                  </label>
                </td>
                <td class="label-cell">Cupcake</td>
                <td class="numeric-cell">305</td>
                <td class="numeric-cell">3.7</td>
                <td class="numeric-cell">67</td>
                <td class="numeric-cell">4.3</td>
                <td class="tablet-only">Don't like it</td>
              </tr>
            </tbody>
          </table>
        </div>
      </div>
      <div class="content-block-title">With title and different actions on select</div>
      <div class="data-table data-table-init card">
        <div class="card-header">
          <div class="data-table-header">
            <div class="data-table-title">Nutrition</div>
            <div class="data-table-actions"><a class="link icon-only"><i class="icon material-icons">sort</i></a><a class="link icon-only"><i class="icon material-icons">more_vert</i></a></div>
          </div>
          <div class="data-table-header-selected">
            <div class="data-table-title-selected"><span class="data-table-selected-count"></span> items selected</div>
            <div class="data-table-actions"><a class="link icon-only"><i class="icon material-icons">delete</i></a><a class="link icon-only"><i class="icon material-icons">more_vert</i></a></div>
          </div>
        </div>
        <div class="card-content">
          <table>
            <thead>
              <tr>
                <th class="checkbox-cell">
                  <label class="form-checkbox">
                    <input type="checkbox"><i></i>
                  </label>
                </th>
                <th class="label-cell">Desert (100g serving)</th>
                <th class="numeric-cell">Calories</th>
                <th class="numeric-cell">Fat (g)</th>
                <th class="numeric-cell">Carbs</th>
                <th class="numeric-cell">Protein (g)</th>
                <th class="tablet-only"><i class="material-icons">message</i> Comments</th>
              </tr>
            </thead>
            <tbody>
              <tr>
                <td class="checkbox-cell">
                  <label class="form-checkbox">
                    <input type="checkbox"><i></i>
                  </label>
                </td>
                <td class="label-cell">Frozen yogurt</td>
                <td class="numeric-cell">159</td>
                <td class="numeric-cell">6.0</td>
                <td class="numeric-cell">24</td>
                <td class="numeric-cell">4.0</td>
                <td class="tablet-only">I like frozen yogurt</td>
              </tr>
              <tr>
                <td class="checkbox-cell">
                  <label class="form-checkbox">
                    <input type="checkbox"><i></i>
                  </label>
                </td>
                <td class="label-cell">Ice cream sandwich</td>
                <td class="numeric-cell">237</td>
                <td class="numeric-cell">9.0</td>
                <td class="numeric-cell">37</td>
                <td class="numeric-cell">4.4</td>
                <td class="tablet-only">But like ice cream more</td>
              </tr>
              <tr>
                <td class="checkbox-cell">
                  <label class="form-checkbox">
                    <input type="checkbox"><i></i>
                  </label>
                </td>
                <td class="label-cell">Eclair</td>
                <td class="numeric-cell">262</td>
                <td class="numeric-cell">16.0</td>
                <td class="numeric-cell">24</td>
                <td class="numeric-cell">6.0</td>
                <td class="tablet-only">Super tasty</td>
              </tr>
              <tr>
                <td class="checkbox-cell">
                  <label class="form-checkbox">
                    <input type="checkbox"><i></i>
                  </label>
                </td>
                <td class="label-cell">Cupcake</td>
                <td class="numeric-cell">305</td>
                <td class="numeric-cell">3.7</td>
                <td class="numeric-cell">67</td>
                <td class="numeric-cell">4.3</td>
                <td class="tablet-only">Don't like it</td>
              </tr>
            </tbody>
          </table>
        </div>
      </div>
      <div class="content-block-title">Alternate header with actions</div>
      <div class="data-table data-table-init card">
        <div class="card-header">
          <div class="data-table-links"><a class="link">Add</a><a class="link">Remove</a></div>
          <div class="data-table-actions"><a class="link icon-only"><i class="icon material-icons">sort</i></a><a class="link icon-only"><i class="icon material-icons">more_vert</i></a></div>
        </div>
        <div class="card-content">
          <table>
            <thead>
              <tr>
                <th class="checkbox-cell">
                  <label class="form-checkbox">
                    <input type="checkbox"><i></i>
                  </label>
                </th>
                <th class="label-cell">Desert (100g serving)</th>
                <th class="numeric-cell">Calories</th>
                <th class="numeric-cell">Fat (g)</th>
                <th class="numeric-cell">Carbs</th>
                <th class="numeric-cell">Protein (g)</th>
                <th class="tablet-only"><i class="material-icons">message</i> Comments</th>
                <th></th>
              </tr>
            </thead>
            <tbody>
              <tr>
                <td class="checkbox-cell">
                  <label class="form-checkbox">
                    <input type="checkbox"><i></i>
                  </label>
                </td>
                <td class="label-cell">Frozen yogurt</td>
                <td class="numeric-cell">159</td>
                <td class="numeric-cell">6.0</td>
                <td class="numeric-cell">24</td>
                <td class="numeric-cell">4.0</td>
                <td class="tablet-only">I like frozen yogurt</td>
                <td class="actions-cell"><a class="link icon-only"><i class="icon material-icons">edit</i></a><a class="link icon-only"><i class="icon material-icons">delete</i></a></td>
              </tr>
              <tr>
                <td class="checkbox-cell">
                  <label class="form-checkbox">
                    <input type="checkbox"><i></i>
                  </label>
                </td>
                <td class="label-cell">Ice cream sandwich</td>
                <td class="numeric-cell">237</td>
                <td class="numeric-cell">9.0</td>
                <td class="numeric-cell">37</td>
                <td class="numeric-cell">4.4</td>
                <td class="tablet-only">But like ice cream more</td>
                <td class="actions-cell"><a class="link icon-only"><i class="icon material-icons">edit</i></a><a class="link icon-only"><i class="icon material-icons">delete</i></a></td>
              </tr>
              <tr>
                <td class="checkbox-cell">
                  <label class="form-checkbox">
                    <input type="checkbox"><i></i>
                  </label>
                </td>
                <td class="label-cell">Eclair</td>
                <td class="numeric-cell">262</td>
                <td class="numeric-cell">16.0</td>
                <td class="numeric-cell">24</td>
                <td class="numeric-cell">6.0</td>
                <td class="tablet-only">Super tasty</td>
                <td class="actions-cell"><a class="link icon-only"><i class="icon material-icons">edit</i></a><a class="link icon-only"><i class="icon material-icons">delete</i></a></td>
              </tr>
              <tr>
                <td class="checkbox-cell">
                  <label class="form-checkbox">
                    <input type="checkbox"><i></i>
                  </label>
                </td>
                <td class="label-cell">Cupcake</td>
                <td class="numeric-cell">305</td>
                <td class="numeric-cell">3.7</td>
                <td class="numeric-cell">67</td>
                <td class="numeric-cell">4.3</td>
                <td class="tablet-only">Don't like it</td>
                <td class="actions-cell"><a class="link icon-only"><i class="icon material-icons">edit</i></a><a class="link icon-only"><i class="icon material-icons">delete</i></a></td>
              </tr>
            </tbody>
          </table>
        </div>
      </div>
      <div class="content-block-title">Collapsible</div>
      <div class="content-block">
        <p>The following table will be collapsed to kind of List View on small screens:</p>
      </div>
      <div class="card data-table data-table-collapsible data-table-init">
        <div class="card-header">
          <div class="data-table-title">Nutrition</div>
          <div class="data-table-actions"><a class="link icon-only"><i class="icon material-icons">sort</i></a><a class="link icon-only"><i class="icon material-icons">more_vert</i></a></div>
        </div>
        <div class="card-content">
          <table>
            <thead>
              <tr>
                <th class="label-cell">Desert (100g serving)</th>
                <th class="numeric-cell">Calories</th>
                <th class="numeric-cell">Fat (g)</th>
                <th class="numeric-cell">Carbs</th>
                <th class="numeric-cell">Protein (g)</th>
              </tr>
            </thead>
            <tbody>
              <tr>
                <td class="label-cell">Frozen yogurt</td>
                <td class="numeric-cell">159</td>
                <td class="numeric-cell">6.0</td>
                <td class="numeric-cell">24</td>
                <td class="numeric-cell">4.0</td>
              </tr>
              <tr>
                <td class="label-cell">Ice cream sandwich</td>
                <td class="numeric-cell">237</td>
                <td class="numeric-cell">9.0</td>
                <td class="numeric-cell">37</td>
                <td class="numeric-cell">4.4</td>
              </tr>
              <tr>
                <td class="label-cell">Eclair</td>
                <td class="numeric-cell">262</td>
                <td class="numeric-cell">16.0</td>
                <td class="numeric-cell">24</td>
                <td class="numeric-cell">6.0</td>
              </tr>
              <tr>
                <td class="label-cell">Cupcake</td>
                <td class="numeric-cell">305</td>
                <td class="numeric-cell">3.7</td>
                <td class="numeric-cell">67</td>
                <td class="numeric-cell">4.3</td>
              </tr>
            </tbody>
          </table>
        </div>
      </div>
    </div>
  </div>
</template>
