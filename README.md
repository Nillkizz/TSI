# TSI

## Example of using ToggleShowingItems:
    <div tsi-items-list-wrapper>
      <h3>...Title...</h3>
      <div tsi-items-list-block 
        data-tsi-items-selector=".center-content > .item" 
        data-tsi-number-of-collapsed-items="2"
        >
          <div class="center-content">
              <div class="item">...Content</div>
              ...Items
          <div>
      </div>
      <a href="javascript:void(0)" 
        tsi-toggle-button 
        data-tsi-expand-text="Полный перечень услуг"
        data-tsi-collapse-text="Свернуть список"
        >Полный перечень услуг</a>
    </div>

## Example of using Accordeon:
    <div id="faq" tsi-accordeon>
        <div data-tsi-toggle="collapse" data-tsi-target=`.faq-1`>
            Who is me?
        </div>
        <div class="faq-1" >
            <div class="collapse-body">
                I'm human!
            </div>
        </div>
    </div>
