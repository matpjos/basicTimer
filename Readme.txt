basic timer implementation.
MX_TIM2_Init();

HAL_TIM_Base_Start_IT(&htim2);

interrupt call-back function.
HAL_TIM_PeriodElapsedCallback(TIM_HandleTypeDef *htim)
{
   //logic to toggle on-board LED
}