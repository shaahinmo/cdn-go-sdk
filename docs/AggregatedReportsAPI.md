# \AggregatedReportsAPI

All URIs are relative to *https://napi.arvancloud.ir/cdn/4.0*

Method | HTTP request | Description
------------- | ------------- | -------------
[**ReportsAggregatedCharts**](AggregatedReportsAPI.md#ReportsAggregatedCharts) | **Get** /reports/aggregated/charts | Charts of aggregated reports for domains
[**ReportsAggregatedDetails**](AggregatedReportsAPI.md#ReportsAggregatedDetails) | **Get** /reports/aggregated/details | List of aggregated reports for domains
[**ReportsAggregatedFilters**](AggregatedReportsAPI.md#ReportsAggregatedFilters) | **Get** /reports/aggregated/filters | Combined filtering data for aggregated reports



## ReportsAggregatedCharts

> ReportsAggregatedCharts200Response ReportsAggregatedCharts(ctx).Domains(domains).ReportType(reportType).CategoryType(categoryType).Pops(pops).Asns(asns).Period(period).Execute()

Charts of aggregated reports for domains



### Example

```go
package main

import (
	"context"
	"fmt"
	"os"
	openapiclient "github.com/shaahinmo/cdn-go-sdk"
)

func main() {
	domains := "example1.com,example2.com" // string | Name of domains. To filter multiple domains separate them using a comma (optional)
	reportType := "reportType_example" // string | Type of report (optional)
	categoryType := "categoryType_example" // string | Category of report (optional)
	pops := "thr-r1c,thr-mci" // string | Names of a pop sites. To filter multiple pops, separate them using a comma (optional)
	asns := "1435,7846" // string | Numbers of ASNs. To filter multiple ASNs, separate them using a comma (optional)
	period := "period_example" // string | Select period -ending now- for report (optional)

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.AggregatedReportsAPI.ReportsAggregatedCharts(context.Background()).Domains(domains).ReportType(reportType).CategoryType(categoryType).Pops(pops).Asns(asns).Period(period).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `AggregatedReportsAPI.ReportsAggregatedCharts``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `ReportsAggregatedCharts`: ReportsAggregatedCharts200Response
	fmt.Fprintf(os.Stdout, "Response from `AggregatedReportsAPI.ReportsAggregatedCharts`: %v\n", resp)
}
```

### Path Parameters



### Other Parameters

Other parameters are passed through a pointer to a apiReportsAggregatedChartsRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **domains** | **string** | Name of domains. To filter multiple domains separate them using a comma | 
 **reportType** | **string** | Type of report | 
 **categoryType** | **string** | Category of report | 
 **pops** | **string** | Names of a pop sites. To filter multiple pops, separate them using a comma | 
 **asns** | **string** | Numbers of ASNs. To filter multiple ASNs, separate them using a comma | 
 **period** | **string** | Select period -ending now- for report | 

### Return type

[**ReportsAggregatedCharts200Response**](ReportsAggregatedCharts200Response.md)

### Authorization

[ApiKey](../README.md#ApiKey), [UserToken](../README.md#UserToken)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## ReportsAggregatedDetails

> ReportsAggregatedDetails200Response ReportsAggregatedDetails(ctx).Domains(domains).CategoryType(categoryType).Pops(pops).Asns(asns).Period(period).Page(page).PerPage(perPage).Execute()

List of aggregated reports for domains



### Example

```go
package main

import (
	"context"
	"fmt"
	"os"
	openapiclient "github.com/shaahinmo/cdn-go-sdk"
)

func main() {
	domains := "example1.com,example2.com" // string | Name of domains. To filter multiple domains separate them using a comma (optional)
	categoryType := "categoryType_example" // string | Category of report (optional)
	pops := "thr-r1c,thr-mci" // string | Names of a pop sites. To filter multiple pops, separate them using a comma (optional)
	asns := "1435,7846" // string | Numbers of ASNs. To filter multiple ASNs, separate them using a comma (optional)
	period := "period_example" // string | Select period -ending now- for report (optional)
	page := int32(56) // int32 | Set the desired page number (optional) (default to 1)
	perPage := int32(56) // int32 | Set how many items returned per page (optional)

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.AggregatedReportsAPI.ReportsAggregatedDetails(context.Background()).Domains(domains).CategoryType(categoryType).Pops(pops).Asns(asns).Period(period).Page(page).PerPage(perPage).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `AggregatedReportsAPI.ReportsAggregatedDetails``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `ReportsAggregatedDetails`: ReportsAggregatedDetails200Response
	fmt.Fprintf(os.Stdout, "Response from `AggregatedReportsAPI.ReportsAggregatedDetails`: %v\n", resp)
}
```

### Path Parameters



### Other Parameters

Other parameters are passed through a pointer to a apiReportsAggregatedDetailsRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **domains** | **string** | Name of domains. To filter multiple domains separate them using a comma | 
 **categoryType** | **string** | Category of report | 
 **pops** | **string** | Names of a pop sites. To filter multiple pops, separate them using a comma | 
 **asns** | **string** | Numbers of ASNs. To filter multiple ASNs, separate them using a comma | 
 **period** | **string** | Select period -ending now- for report | 
 **page** | **int32** | Set the desired page number | [default to 1]
 **perPage** | **int32** | Set how many items returned per page | 

### Return type

[**ReportsAggregatedDetails200Response**](ReportsAggregatedDetails200Response.md)

### Authorization

[ApiKey](../README.md#ApiKey), [UserToken](../README.md#UserToken)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## ReportsAggregatedFilters

> ReportsAggregatedFilters200Response ReportsAggregatedFilters(ctx).Domains(domains).Execute()

Combined filtering data for aggregated reports



### Example

```go
package main

import (
	"context"
	"fmt"
	"os"
	openapiclient "github.com/shaahinmo/cdn-go-sdk"
)

func main() {
	domains := "example1.com,example2.com" // string | Name of domains. To filter multiple domains separate them using a comma (optional)

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.AggregatedReportsAPI.ReportsAggregatedFilters(context.Background()).Domains(domains).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `AggregatedReportsAPI.ReportsAggregatedFilters``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `ReportsAggregatedFilters`: ReportsAggregatedFilters200Response
	fmt.Fprintf(os.Stdout, "Response from `AggregatedReportsAPI.ReportsAggregatedFilters`: %v\n", resp)
}
```

### Path Parameters



### Other Parameters

Other parameters are passed through a pointer to a apiReportsAggregatedFiltersRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **domains** | **string** | Name of domains. To filter multiple domains separate them using a comma | 

### Return type

[**ReportsAggregatedFilters200Response**](ReportsAggregatedFilters200Response.md)

### Authorization

[ApiKey](../README.md#ApiKey), [UserToken](../README.md#UserToken)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)

