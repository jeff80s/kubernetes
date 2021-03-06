# doc.go is managed by kazel, so gazelle should ignore it.
# gazelle:exclude doc.go

package(default_visibility = ["//visibility:public"])

load("//pkg/generated/openapi:def.bzl", "openapi_library")
load("//build:openapi.bzl", "openapi_go_prefix", "openapi_vendor_prefix")

openapi_library(
    name = "go_default_library",
    srcs = ["doc.go"],
    go_prefix = openapi_go_prefix,
    openapi_targets = [
        "pkg/apis/abac/v0",
        "pkg/apis/abac/v1beta1",
        "pkg/apis/componentconfig/v1alpha1",
        "pkg/kubelet/apis/kubeletconfig/v1beta1",
        "pkg/proxy/apis/kubeproxyconfig/v1alpha1",
        "pkg/version",
    ],
    tags = ["automanaged"],
    vendor_prefix = openapi_vendor_prefix,
    vendor_targets = [
        "k8s.io/api/admission/v1beta1",
        "k8s.io/api/admissionregistration/v1alpha1",
        "k8s.io/api/admissionregistration/v1beta1",
        "k8s.io/api/apps/v1",
        "k8s.io/api/apps/v1beta1",
        "k8s.io/api/apps/v1beta2",
        "k8s.io/api/authentication/v1",
        "k8s.io/api/authentication/v1beta1",
        "k8s.io/api/authorization/v1",
        "k8s.io/api/authorization/v1beta1",
        "k8s.io/api/autoscaling/v1",
        "k8s.io/api/autoscaling/v2beta1",
        "k8s.io/api/batch/v1",
        "k8s.io/api/batch/v1beta1",
        "k8s.io/api/batch/v2alpha1",
        "k8s.io/api/certificates/v1beta1",
        "k8s.io/api/core/v1",
        "k8s.io/api/events/v1beta1",
        "k8s.io/api/extensions/v1beta1",
        "k8s.io/api/imagepolicy/v1alpha1",
        "k8s.io/api/networking/v1",
        "k8s.io/api/policy/v1beta1",
        "k8s.io/api/rbac/v1",
        "k8s.io/api/rbac/v1alpha1",
        "k8s.io/api/rbac/v1beta1",
        "k8s.io/api/scheduling/v1alpha1",
        "k8s.io/api/scheduling/v1beta1",
        "k8s.io/api/settings/v1alpha1",
        "k8s.io/api/storage/v1",
        "k8s.io/api/storage/v1alpha1",
        "k8s.io/api/storage/v1beta1",
        "k8s.io/apiextensions-apiserver/pkg/apis/apiextensions/v1beta1",
        "k8s.io/apimachinery/pkg/api/resource",
        "k8s.io/apimachinery/pkg/apis/meta/v1",
        "k8s.io/apimachinery/pkg/apis/meta/v1beta1",
        "k8s.io/apimachinery/pkg/apis/testapigroup/v1",
        "k8s.io/apimachinery/pkg/runtime",
        "k8s.io/apimachinery/pkg/util/intstr",
        "k8s.io/apimachinery/pkg/version",
        "k8s.io/apiserver/pkg/apis/audit/v1alpha1",
        "k8s.io/apiserver/pkg/apis/audit/v1beta1",
        "k8s.io/apiserver/pkg/apis/example/v1",
        "k8s.io/apiserver/pkg/apis/example2/v1",
        "k8s.io/client-go/pkg/apis/clientauthentication/v1alpha1",
        "k8s.io/client-go/pkg/version",
        "k8s.io/kube-aggregator/pkg/apis/apiregistration/v1",
        "k8s.io/kube-aggregator/pkg/apis/apiregistration/v1beta1",
        "k8s.io/metrics/pkg/apis/custom_metrics/v1beta1",
        "k8s.io/metrics/pkg/apis/external_metrics/v1beta1",
        "k8s.io/metrics/pkg/apis/metrics/v1alpha1",
        "k8s.io/metrics/pkg/apis/metrics/v1beta1",
    ],
)

filegroup(
    name = "package-srcs",
    srcs = glob(["**"]),
    tags = ["automanaged"],
    visibility = ["//visibility:private"],
)

filegroup(
    name = "all-srcs",
    srcs = [":package-srcs"],
    tags = ["automanaged"],
)
