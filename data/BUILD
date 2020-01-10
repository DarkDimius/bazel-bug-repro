[genrule(
    name = "data_{}".format(ii),
    outs = ["data_{}.txt".format(ii)],
    cmd = "sleep 5; touch $@",
    visibility = ["//visibility:public"],
) for ii in range(100)]
