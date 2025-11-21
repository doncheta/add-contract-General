# add-contract-General
  contract General is IGeneral {
    function hourlyRate() external pure override returns (uint) {
        return 20;
       }
