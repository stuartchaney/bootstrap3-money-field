# Bootstrap 3 Money Field

Prepend input fields with a currency symbol in [bootstrap 3](http://getbootstrap.com/).

###HTML
Add an amount class

    <input type="text" class="amount" name="item_price" />
    
###Javascript

    <script type="text/javascript">
    $(function(){
      var options = {
        width: 100,
        symbol: '$'
      };
      $('.amount').money_field(options);
    });
  </script>
