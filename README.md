# iOS_BillCalc

iOS_BillCalc app allows the user to generate the bill amount of hydro consumption.</br></br>
The user is asked to input the following through UITextField:
- On-peak usage in kWh (Double)
- Off-peak usage in kWh (Double)
- Mid-peak usage in kWh (Double)
</br>

The following information is used to perform calculations:
- The charges for on-peak usage are $0.132 per kWh
- The charges for off-peak usage are $0.065 per kWh
- The charges for mid-peak usage are $0.094 per kWh
- The total consumption charge is combined total of on-peak charges, off-peak charges and mid-peak charges
- Calculate the HST which is 13% of total consumption charges
- Calculate the provincial rebate(discount) which is 8% of the total consumption charges
- The net bill amount is total consumption charges + HST – provincial rebate

#
<a href="https://drive.google.com/file/d/1m0YUBxowgWcpPEQ6VwKK2CmKMDcrClUn/view?usp=sharing" target="_blank">Demo video</a>
