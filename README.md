# gift_html
<!DOCTYPE html>
<html>

<head>
    <link rel="stylesheet" href="https://stackpath.bootstrapcdn.com/bootstrap/4.5.2/css/bootstrap.min.css" integrity="sha384-JcKb8q3iqJ61gNV9KGb8thSsNjpSL0n8PARn9HuZOnIxN0hoP+VmmDGMN5t9UJ0Z" crossorigin="anonymous" />
    <script src="https://code.jquery.com/jquery-3.5.1.slim.min.js" integrity="sha384-DfXdz2htPH0lsSSs5nCTpuj/zy4C+OGpamoFVy38MVBnE+IbbVYUew+OrCXaRkfj" crossorigin="anonymous"></script>
    <script src="https://cdn.jsdelivr.net/npm/popper.js@1.16.1/dist/umd/popper.min.js" integrity="sha384-9/reFTGAW83EW2RDu2S0VKaIzap3H66lZH81PoYlFhbGU+6BZp6G7niu735Sk7lN" crossorigin="anonymous"></script>
    <script src="https://stackpath.bootstrapcdn.com/bootstrap/4.5.2/js/bootstrap.min.js" integrity="sha384-B4gt1jrGC7Jh4AgTPSdUtOBvfO8shuf57BaghqFfPlYxofvL8/KUEfYiJOMMV+rV" crossorigin="anonymous"></script>
</head>

<body>
    <div class="gift-section m-4 p-3">

        <div class="col-12">
            <h1 class="heading">Thank you for being a valuable customer to us</h1>
            <p class="paragraph">We have a surprise gift for you</p>
        </div>
        <div class="col-12">
            <div class="text-center">
                <img src="https://d1tgh8fmlzexmh.cloudfront.net/ccbp-responsive-website/thanking-customers-section-img.png" class="image mb-3" />
            </div>
        </div>

        <button type="button" class="custom-button" data-toggle="modal" data-target="#exampleModal">
            Redeem Gift
        </button>
        <div class="modal fade" id="exampleModal" tabindex="-1" aria-labelledby="exampleModalLabel" aria-hidden="true">
            <div class="modal-dialog mt-5">
                <div class="modal-content">
                    <div class="modal-header">
                        <h5 class="modal-title thanking-customers-section-modal-title" id="exampleModalLabel">
                            Gift Voucher
                        </h5>
                        <button type="button" class="close" data-dismiss="modal" aria-label="Close">
                            <span aria-hidden="true">&times;</span>
                        </button>
                    </div>
                    <div class="modal-body">
                        <img src="https://d1tgh8fmlzexmh.cloudfront.net/ccbp-responsive-website/gift-voucher-img.png" class="w-100" />
                    </div>
                    <div class="modal-footer">
                        <button type="button" class="btn btn-secondary" data-dismiss="modal">
                            Close
                        </button>


                    </div>
                </div>
            </div>
        </div>
    </div>
    </div>
</body>

</html>
