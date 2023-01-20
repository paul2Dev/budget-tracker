<script>

</script>

<main>
  <form class="bg-white p-6 rounded-lg shadow-md">
    <h2 class="text-lg font-medium mb-4">Add Budget Entry</h2>
    <div class="flex gap-3 justify-left flex-wrap mb-4">
      <div class="">
        <label class="block text-gray-700 font-medium mb-2" for="name">Name</label>
        <input class="bg-gray-200 p-2 rounded-lg w-full" type="text" id="name" name="name">
      </div>
      <div class="">
        <label class="block text-gray-700 font-medium mb-2" for="amount">Amount</label>
        <input class="bg-gray-200 p-2 rounded-lg w-full" type="number" id="amount" name="amount">
      </div>
      <div class="">
        <label class="block text-gray-700 font-medium mb-2" for="category">Category</label>
        <select class="bg-gray-200 p-2 rounded-lg w-full" id="category" name="category">
          <option value="job">Job</option>
          <option value="housing">Housing</option>
          <option value="bills">Bills</option>
          <option value="food">Food</option>
        </select>
      </div>
      <div class="">
        <label class="block text-gray-700 font-medium mb-2" for="date">Date</label>
        <input class="bg-gray-200 p-2 rounded-lg w-full" type="date" id="date" name="date">
      </div>
      <div class="">
        <label class="block text-gray-700 font-medium mb-2" for="who_paid">Who Paid</label>
        <select class="bg-gray-200 p-2 rounded-lg w-full" id="who_paid" name="who_paid">
          <option value="self">Self</option>
          <option value="other">Other</option>
        </select>
      </div>
      <div class="self-end">
        <button class="bg-blue-500 text-white py-2 px-4 rounded-lg hover:bg-blue-600">Submit</button>
      </div>
    </div>
  </form>
  
  

  <div class="bg-white p-6 rounded-lg shadow-md">
    <h2 class="text-lg font-medium mb-4">Budget Entries</h2>
    <div class="w-full">
      <div class="flex justify-between font-medium text-sm bg-gray-200 p-2 mb-2">
          <div class="w-1/5">Name</div>
          <div class="w-1/5">Amount</div>
          <div class="w-1/5">Category</div>
          <div class="w-1/5">Date</div>
          <div class="w-1/5">Who Paid</div>
      </div>
      <div class="flex justify-between p-2 mb-2">
          <div class="w-1/5">Salary</div>
          <div class="w-1/5">$5,000</div>
          <div class="w-1/5">Job</div>
          <div class="w-1/5">01/01/2022</div>
          <div class="w-1/5">Employer</div>
      </div>
      <div class="flex justify-between p-2 mb-2">
          <div class="w-1/5">Rent</div>
          <div class="w-1/5">$1,200</div>
          <div class="w-1/5">Housing</div>
          <div class="w-1/5">01/15/2022</div>
          <div class="w-1/5">Self</div>
      </div>
      <div class="flex justify-between p-2 mb-2">
          <div class="w-1/5">Utilities</div>
          <div class="w-1/5">$300</div>
          <div class="w-1/5">Bills</div>
          <div class="w-1/5">01/20/2022</div>
          <div class="w-1/5">Self</div>
      </div>
      <div class="flex justify-between p-2 mb-2">
          <div class="w-1/5">Groceries</div>
          <div class="w-1/5">$500</div>
          <div class="w-1/5">Food</div>
          <div class="w-1/5">01/25/2022</div>
          <div class="w-1/5">Self</div>
      </div>
    </div>
  </div>  
</main>


